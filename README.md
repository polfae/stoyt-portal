# Stoyt Portal v5.4.0

Phase 3: public competition share links and passwords.

Updates:
- Each competition can now be shared using a competition-specific link
- The link format is `?competition=COMPETITION_ID`
- Public users do not need a login
- Public users enter the competition password chosen by Stoyt-admin
- Public users only see that one competition
- Public users can mark tasks as done, edit tasks, add tasks, add responsible people and assign responsible people
- Public users do not see the dashboard, templates or revenue calculator
- Stoyt-admin keeps full access to everything
- Firestore online saving is kept

Notes:
- Competition passwords are currently stored in the portal state as plain text for this phase.
- A later security phase should move password validation into a safer server/rules setup.

Open `index.html` in your browser.
