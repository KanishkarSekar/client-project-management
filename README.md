# ProjectPro — Client Project Management Platform

**Internship task:** WD-SW-005  
**Student code:** DAS-SW-005  
**Company:** Data Alcott Systems  
**Stack:** HTML5, CSS3, Vanilla JavaScript, localStorage, optional Chart.js

## Overview
ProjectPro is a responsive frontend-only client project management demo. It includes a dashboard, project CRUD, task CRUD and Kanban board, milestones, time logs, client management, local file sharing, team management, CSV reports, simulated role selection, notifications, and dark mode.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser. For best results, use a local static server such as VS Code Live Server.
3. Choose a demo role and enter the workspace.
4. Create and edit sample records. Changes are saved in your browser's localStorage.

No database, build step, or API key is required. Chart.js and the Inter font are loaded from CDNs; the rest of the application is plain HTML, CSS, and JavaScript.

## Data and security notes
- Seed data is provided for demonstration. Use the app's forms to add, edit, and delete records.
- Data remains in the current browser profile and can be cleared by clearing site data.
- Login is simulated for demonstration only. It does not provide secure authentication or real role-based access control.
- File uploads are kept as browser data URLs and limited to 2 MB per file to reduce localStorage pressure. This is not a production file-sharing service.
- CSV reports are generated in the browser. PDF export and email delivery are not implemented; notifications are simulated in-app.
- The timeline/Gantt view is not included in this first version; project dates and milestone deadlines are tracked in the project and milestone pages.

## Pages
Dashboard · Projects · Tasks (Kanban/List) · Milestones · Time Tracking · Clients · Files · Team · Reports

## Submission links
- Internship task/blog submission: https://www.freeinternships.in/blog/
- GitHub repository: add your public repository URL here.
- Live website: add your GitHub Pages / Netlify / Vercel URL here.
- YouTube demo: add your public or unlisted video URL here.

## Suggested screenshots
Capture desktop and mobile views of Dashboard, Projects, Tasks/Kanban, Milestones, Time Tracking, Clients, Files, Team, Reports, and the mobile navigation.

## License
For educational and internship-task demonstration purposes.
