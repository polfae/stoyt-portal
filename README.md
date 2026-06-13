# Stoyt Portal v5.3.0

Phase 2: Firestore online storage for the portal state.

Updates:
- Added Firestore connection using the existing Firebase project
- Competitions and templates are now saved online to Firestore
- Portal loads competitions/templates from Firestore after Stoyt-admin login
- Previous local dummy data is intentionally not imported
- Added an online save status in the sidebar
- Current competition planner, calculator, PDF/filter behavior and design updates are kept

Firestore document used:
- Collection: `portal`
- Document: `state`

Important Firebase setup:
- Firebase Authentication must be enabled
- Firestore Database must be enabled
- During testing, Firestore can be in test mode

Next backend phase:
- Create share links for individual competitions
- Add optional competition password access
- Add public/password competition mode

Password users in later phases:
- Can mark tasks as done
- Can edit tasks
- Can add tasks
- Can add and assign responsible people

Open `index.html` in your browser.
