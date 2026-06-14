# Stoyt Portal v5.4.7

Deep public-layout fix.

What was wrong:
- The code was trying to hide `#backToDashboardBtn`, but the real button ID is `#backToDashboard`.
- The code was trying to center `.main-content`, but the real main container class is `.main`.

Updates:
- Fully removes the real `#backToDashboard` button from the DOM in public competition mode
- Centers the actual `.main` / `#checklistView` structure across the browser width
- Adds direct inline style fallback from JavaScript, not only CSS
- Keeps public competition tools identical to admin checklist view
- Firestore saving, public password access, admin login, planner and calculator are kept

Open `index.html` in your browser.
