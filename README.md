# Stoyt Portal v5.7.0

Dynamic roles update.

Updates:
- Removed the fixed/pre-entered competition roles from the user flow.
- Competitions now use custom roles created by the user.
- The roles modal starts empty when no roles have been created.
- Added “+ Stovna leiklut” in the roles modal.
- Each competition role has:
  - role title
  - one or more person fields
  - add/remove person controls
  - delete role control
- Templates can now include roles.
- Template roles only store:
  - role title
  - number of required people
- When creating a competition from a template, those template roles are copied into the competition with empty person fields.
- Existing old role data is migrated into the new dynamic role structure if present.
- Task handling, public links/passwords, Firebase Auth, Firestore saving, planner and calculator are kept.

Base: user-uploaded Stoyt-Portal.zip.
Open `index.html` in your browser.
