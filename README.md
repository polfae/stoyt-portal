# Stoyt Portal v5.5.6

New task modal create/cancel fix.

Updates:
- Clicking “+ Nýggj uppgáva” opens the task modal without creating the task first.
- The task is only created when the user clicks “Goym broytingar”.
- Clicking X while creating a new task closes the modal and creates nothing.
- Clicking X while editing an existing task discards unsaved changes.
- “Strika uppgávu” still deletes an existing task.
- For an unsaved new task, “Strika uppgávu” simply cancels/closes the modal.
- Task modal behavior is separate from login/logout.
- Firestore saving, public password access, admin login, planner and calculator are kept.

Base: user-uploaded v5.5.4 through v5.5.5 branch.
Open `index.html` in your browser.
