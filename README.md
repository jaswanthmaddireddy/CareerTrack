# CareerTrack — Job Application Tracker

CareerTrack is a responsive front-end project for organizing internship and job applications, built with plain HTML, CSS, and JavaScript.

## Features
- Add, edit, and delete application records
- Track company, role, application date, status, location, and notes
- Dashboard counts for total applications, interviews, offers, and in-progress applications
- Search by company, role, location, or notes
- Filter by status and sort by date or company
- Export all saved records to CSV
- Save data in browser `localStorage`
- Responsive design and required-field/date validation

## Tech stack
HTML5, CSS3 (Grid/Flexbox/media queries), vanilla JavaScript, localStorage, Blob API.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Optionally use VS Code with the Live Server extension while developing.

No build step or dependency installation is required.

## Structure
```text
CareerTrack/
├── index.html
├── style.css
├── app.js
├── README.md
└── .gitignore
```

## Data storage and privacy
Records are saved in the current browser under `careertrack-applications-v1`. They are not uploaded to a server and do not sync between devices. Clearing browser site data may remove them; export CSV backups when needed.

## Manual test checklist
- [ ] Add a valid record
- [ ] Try saving with company or role missing
- [ ] Try a future application date
- [ ] Edit a record and confirm changes
- [ ] Delete a record; test both cancel and confirm
- [ ] Search by company and role
- [ ] Filter each status
- [ ] Sort newest, oldest, and company A–Z
- [ ] Refresh and confirm data persists
- [ ] Export CSV and open it in a spreadsheet app
- [ ] Test a narrow/mobile viewport
- [ ] Delete all records and check the empty state

## Known limitations
- No authentication, backend, or shared database
- Data is local to the browser/device
- CSV export includes all records, not only filtered results
- Does not submit applications or contact employers

## Possible future improvements
- Backend API and database
- Interview reminders
- Application-stage charts
- Validated CSV import
- Automated tests

## Resume note
Add this project to your resume only after running and testing it. Describe features you personally verified, and do not claim usage, performance, or deployment unless you have evidence.

## License
Add a license file if you want to specify formal reuse terms.
