# Stoyt Portal v5.4.8

Definitive public competition layout fix.

Root cause:
- Earlier fixes still depended on public/auth classes being applied after load.
- The previous JavaScript also forced the app shell to `display: block`, which worked against the original grid layout.
- The public view needs the app grid to become `0 + full width`, not a shifted block.

Updates:
- Adds an early `html.public-competition-route` class before CSS loads when the URL has `?competition=...`
- Uses the real selectors: `#backToDashboard`, `.main`, `#appShell`, and `#checklistView`
- Fully hides/removes the Aftur button in public competition links
- Centers the public competition content using the full browser width
- Keeps the public competition screen otherwise identical to the admin checklist view
- Firestore saving, public password access, admin login, planner and calculator are kept

Open `index.html` in your browser.
