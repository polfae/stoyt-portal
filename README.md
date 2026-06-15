# Stoyt Portal v5.5.5

Task modal cancel behavior fix.

Updates:
- The X button in the task modal now cancels/discards changes
- If a new task is opened and the user clicks X, the new task is not created
- If an existing task is edited and the user clicks X, unsaved changes are discarded
- The bottom buttons keep their meaning:
  - Strika uppgávu = delete task
  - Goym broytingar = save/create task
- The task modal is separate from login/logout behavior
- Firestore saving, public password access, admin login, planner and calculator are kept

Base: user-uploaded v5.5.4.
Open `index.html` in your browser.
