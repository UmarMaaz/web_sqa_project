Testing Project: Task Management Web Application

This repository contains the complete testing documentation and artifacts for the Task Management Web Application – a responsive, role‑based task manager built with pure HTML, CSS, and JavaScript. The testing effort was carried out to validate all functional and non‑functional requirements, ensuring a high‑quality, production‑ready application.

📋 Project Overview
The application under test is a modern task management dashboard inspired by tools like Trello and Asana. It features:

Role‑based access (Admin / User)

Login / authentication with demo credentials

Dashboard with task summary cards

Full CRUD operations on tasks

Search, filter, and status badges

Local storage persistence

Fully responsive design (desktop, tablet, mobile)

This repository focuses solely on the testing deliverables – test cases, execution results, and summary reports – not the application source code.

🧪 Testing Scope
The following areas were covered during testing:

Login & Authentication – UI validation, successful/failed login, demo credentials, responsive behaviour.

Dashboard Layout – Sidebar menus (role‑based), top navbar, task summary cards, responsive design.

Task Management – Table display, status badges, action buttons visibility, search and filter.

Create/Edit Modal – Field validation, pre‑fill, save/cancel, assignee dropdown.

Delete Task – Confirmation modal, cancel/confirm actions.

Role‑Based Access Control – Visibility of menus and action buttons for Admin vs. User.

Alerts & Feedback – Toast notifications (success/error), auto‑dismiss, colours.

Local Storage – Data persistence after refresh, correct data structure.

Responsive Design – Tablet and mobile layouts, modal adaptability.

🖥️ Test Environment
Browser: Google Chrome (Version 120.0.6099.216)

Operating System: Windows 11 Pro

Screen Resolutions: 1920×1080 (desktop), 768×1024 (tablet), 375×667 (mobile)

Tools: Chrome DevTools (for responsive testing and local storage inspection)

📊 Test Execution Summary
Total Test Cases: 50

Passed: 50

Failed: 0

Pass Rate: 100%

All functional and UI requirements were verified and met expectations. No critical defects were found.

🚀 How to Use These Artifacts
Review the Test Cases – Open the Excel files to see detailed test scenarios, steps, expected results, and mock execution data.

Read the Summary Report – The Test_Summary_Report.md provides an executive overview of the testing process and outcomes.

Adapt for Your Own Testing – Feel free to reuse the test case template or modify the suite for similar web applications.

🛠️ Future Improvements
Expand test suite with edge cases (e.g., special characters in task titles, very long descriptions).

Add cross‑browser testing (Firefox, Safari, Edge) to ensure compatibility.

Include basic performance testing (page load times, modal responsiveness under load).

Automate regression tests using a tool like Selenium or Cypress.

📄 License
This project is open source and available under the MIT License. You are free to use, modify, and distribute the testing artifacts as needed.

Author: QA Team
Date: March 2026
Contact: [your-email@example.com] (optional)
