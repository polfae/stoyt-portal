# Stoyt Portal v5.5.6

New task modal create/cancel fix.

Important:
- This version is based directly on the user-uploaded v5.5.4 base.
- The task modal X button is kept.

Updates:
- Clicking “+ Nýggj uppgáva” opens the task modal without creating the task first
- The task is only created when the user clicks “Goym broytingar”
- Clicking X while creating a new task closes the modal and creates nothing
- Clicking X while editing an existing task discards unsaved changes
- “Strika uppgávu” still deletes an existing task
- For an unsaved new task, “Strika uppgávu” simply cancels/closes the modal
- Task modal behavior is separate from login/logout
- Firestore saving, public password access, admin login, planner and calculator are kept

Open `index.html` in your browser.
