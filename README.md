# Stoyt Portal v5.5.7

Second urgent login fix.

What changed:
- The admin login handler is now registered much earlier in the script
- The setup has a guard so it is not registered twice
- A small form-submit safety guard prevents the login form from reloading/clearing the page
- This makes login resilient even if a later optional UI element has an issue
- All previous v5.5.6/v5.5.5 UI changes are kept

Open `index.html` in your browser.
