## Hi, I'm Felipe 👋
My name is Felipe Araújo, an apprentice SOC analyst and a non-graduate of School Goiania Associated ESUP. I have a strong interest in cybersecurity; I am currently studying and applying my knowledge of security and privacy to the websites I develop. I enjoy working in both the systems development and security fields.

**How to reach me!**

<a href="https://www.linkedin.com/in/felipe-ar4uj0" target="_blank">
  <img src="https://img.shields.io/badge/-felipe--ar4uj0-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge">
</a>
<a href="https://instagram.com/felipe.araujoo16" target="_blank">
  <img src="https://img.shields.io/badge/-felipe.araujoo16-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Badge">
</a>
<a href="mailto:felipegalvaocontatos@gmail.com">
  <img src="https://img.shields.io/badge/-felipegalvaocontatos-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Badge">
</a>

**🔭 I’m currently working on**
- Building internal systems as a developer on the IT team at ESUP College, the same institution where I am currently studying.
- Running the college's Moodle platform, where students and faculty carry out their online activities.
- Putting security into practice: Microsoft Entra ID SSO, role-based access control and security scanning (Gitleaks, Semgrep, Trivy) in CI/CD pipelines.

**🌱 I’m currently learning**
- Website security for sites containing sensitive data
- The Fundamentals of Cybersecurity and Its Importance in the Digital World
- How to implement cybersecurity in systems
- Computer networking
- Going deeper into Python
- Taking the Santander cybersecurity course

## 🚀 Projects

Systems I built or helped build for the IT team at ESUP College. The source code is private and owned by the institution, so this section covers the problem, the solution and the stack.

### AlocaESUP · Room and space booking
Web app to book and manage rooms across three campus buildings. In production.
- Year, month and week calendars with conflict prevention and multi-room bookings saved in a single transaction
- Payment tracking with receipt upload, financial dashboard and Excel export
- Per-building data isolation, role-based access, local login plus Microsoft SSO
- Imported 81 activities from Microsoft Planner with no duplicates
- CI/CD with security scanners and automatic VM deploy with backup

`Node.js` `PostgreSQL` `Docker` `GitHub Actions` `Cloudflare Tunnel`

### ESUP News · News portal and newsletter by course
Collects news for each course area, lets staff curate it and sends a weekly segmented newsletter.
- Relevance and quality scores (0–100), trusted/blocked domains, broken-link detection
- Double opt-in with signed links and privacy-preserving open tracking
- Admin panel with Microsoft Entra ID (OIDC + PKCE) and per-role permissions
- AI-generated social post drafts for coordinators (IBM watsonx.ai) with a non-AI fallback
- Rate limiting, uptime monitoring with alerts, database migrations

`Node.js` `Express` `PostgreSQL` `Docker` `Cloudinary`

### CoordenaESUP · Task management for academic coordination
Kanban board and task list for the board of directors and course coordinators, with a custom interface built on Kanboard.
- Microsoft SSO only, with separate roles for directors and coordinators
- Version checks that stop an old edit from overwriting a newer one
- Attachments with authorized download, accessible drag-and-drop, keyboard shortcuts
- Pipeline with Gitleaks, Semgrep and Trivy, image published to GHCR and deployed automatically

`PHP` `Kanboard` `SQLite` `Docker` `GitHub Actions`

### EnadeESUP · Moodle plugin for ENADE exam prep
Moodle plugin that prepares Information Systems students for ENADE 2026.
- Full mock exams (45 multiple-choice questions + 1 essay, 4 hours) with question hints
- Personalized practice that favors questions the student got wrong or hasn't seen
- Teacher review and approval flow with audit trail and AI question generation under quotas

`PHP` `Moodle` `Docker`

### Edu AI · AI agent for lead qualification *(team project)*
Dashboard for an AI agent that answers, re-engages and qualifies prospective students.
**My role:** front-end, requirements management and access governance.
- Supports Gemini, OpenAI and Claude, and groups consecutive messages the way WhatsApp chats arrive
- Four access levels enforced in the backend, audit log, request tracing
- Lead import (CSV/XLSX), knowledge base upload, Meta Lead Ads sync, live metrics

`Python` `FastAPI` `SQLAlchemy` `React` `TypeScript`

### AutoProvas · Exam generation and automated grading *(team project)*
Replaced a paid tool (Evalbee). Generates exams, grades scanned answer sheets and publishes the grades to students.
- Exams generated as PDF with QR codes from each course's own question bank
- Grading by computer vision: reads the QR code and answer bubbles
- Student grade portal, email and WhatsApp notices, Google Drive and Excel exports

`Python` `Flask` `OpenCV` `PyMuPDF` `PostgreSQL` `PHP`

### ESUP Clicks · Photo kiosk for campus events *(team project)*
Touchscreen photo booth for the back-to-school event, where the student's phone works as the camera.
- Live video from phone to kiosk over WebRTC, commands over Socket.IO
- Frames synced from Google Drive, photos sent by email, 300 dpi print sheets generated
- Device pairing with a team key, input sanitization, short data retention (LGPD)

`Node.js` `TypeScript` `WebRTC` `Socket.IO` `Google Drive API`

## Top Technologies
<div align="left">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />
  <img src="https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
  <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Moodle-F98012?style=for-the-badge&logo=moodle&logoColor=white" />
</div>

## Skills
<div align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Antigravity-663399?style=for-the-badge&logo=magnet&logoColor=white" />
  <a href="https://tryhackme.com/p/felipearaujo7e" target="_blank">
    <img src="https://img.shields.io/badge/-TRYHACKME-red?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe Badge">
  </a>
</div>
