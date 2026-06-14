# Stoyt Portal v5.5.6

Urgent login fix.

Issue fixed:
- v5.5.5 removed the top-right X button from the task modal
- The JavaScript still tried to attach an event listener to that removed button
- This caused a runtime error and stopped the rest of the script before the login handler was active
- Result: pressing login behaved like a normal form submit and cleared the email/password fields

Update:
- The missing task-modal close button listener is now optional
- Login works again
- The task modal still does not show the top-right X
- All v5.5.5 UI changes are kept
- Firestore saving, public password access, admin login, planner and calculator are kept

Open `index.html` in your browser.
