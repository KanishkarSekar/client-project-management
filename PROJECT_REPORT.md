# ProjectPro — Project Report
**Task ID:** WD-SW-005 | **Student Code:** DAS-SW-005

## Objective
ProjectPro is a frontend-only client project management platform designed to help a small delivery team organize client projects, assign tasks, track milestones, record work hours, share project resources, and review delivery progress in one workspace. The goal is to demonstrate practical web development skills through a responsive and interactive application without requiring a database.

## Technology
The application uses semantic HTML5 for structure, CSS3 for responsive styling and dark mode, and vanilla JavaScript for state management, rendering, form validation, search, filtering, CSV exports, and simulated login. JavaScript objects and arrays represent projects, tasks, milestones, time logs, clients, files, and team members. Browser localStorage persists workspace changes. Chart.js is used optionally for the dashboard's task distribution chart.

## Features
The dashboard summarizes projects, tasks, recorded hours, upcoming deadlines, and recent activity. Project management supports creating, editing, deleting, and filtering projects with client, budget, timeline, status, and progress details. Tasks can be created, assigned, prioritized, edited, filtered, and moved between To Do, In Progress, and Done on a Kanban board or reviewed in a table. Milestones track key project checkpoints. Time tracking records hours and notes against tasks. Client and team pages manage contact details, roles, and project assignments. The file page allows small files to be attached locally to projects. Reports summarize progress, budgets, tasks, and time, with CSV export. The layout adapts to desktop and mobile widths, and includes a dark mode toggle.

## Learning outcomes
This project practices semantic page structure, reusable CSS patterns, responsive layout design, DOM manipulation, event delegation, form-driven CRUD workflows, filtering and sorting, localStorage persistence, browser file APIs, CSV generation, and chart integration. It also demonstrates how project-management data relates across projects, tasks, clients, team members, and time entries.

## Challenges and limitations
Keeping related records consistent when a project, task, or client is deleted required explicit cleanup logic. Responsive Kanban columns need horizontal scrolling on narrow screens. Since this is a browser-only educational prototype, authentication is simulated, data is stored only in the current browser, and uploaded files are not shared between users. The 2 MB upload limit reduces the risk of exceeding browser storage. Production deployment would require server-side authentication, authorization, shared storage, database persistence, and secure file handling.

## Conclusion
ProjectPro delivers a working demonstration of core client project management workflows using the required frontend technologies. It can be hosted as a static website on GitHub Pages, Netlify, or Vercel. Before submission, the developer should test all forms, capture requested desktop/mobile screenshots, add actual repository and deployment links to the README, and record a 3–5 minute demonstration.
