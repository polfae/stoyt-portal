# Stoyt Portal v5.5.8

Task modal / login separation bug fix.

Bug fixed:
- Saving a task caused the app to behave like it logged out and back in
- This happened because the previous emergency login workaround affected form behavior
- The real issue was the removed task-modal X button still being referenced in JavaScript

Updates:
- Removed the emergency login form workaround
- Kept the task-modal X button removed from the HTML
- Made the old task-modal X listener safe/optional
- Kept the normal task form submit handler with `event.preventDefault()`
- Saving a task now only saves the task, closes the modal and updates the competition view
- Firebase login/logout is not touched by the task modal
- Firestore saving, public password access, admin login, planner and calculator are kept

Open `index.html` in your browser.
