# Sudheer Veeravalli — Personal Profile & Program Status Tracker

Welcome to my personal workspace repository! This repository hosts my professional resume website and a companion **Program Status Tracker** tool.

## 🚀 Live Site Features

### 1. Personal Resume & Portfolio (`index.html`)
A responsive, professional portfolio website highlighting:
* **Experience**: 20+ years of leading enterprise technology, DeFi, and Healthcare programs.
* **Core Competencies**: Program Management, DevOps & CI/CD automation, Cloud Engineering (AWS/Azure), Agile, ITIL.
* **Credentials**: TOGAF 9, ITIL 4, AWS Developer Associate, PagerDuty Foundational Practitioner.
* **Interests & Contact info**: Quick social connections and inquiries.

### 2. Dynamic Program Status Tracker (`program-tracker.html`)
A premium dashboard to monitor sub-project status, progress, milestones, risks, and weekly updates.
* **Modern Glassmorphic Design**: Clean UI with responsive fluid layouts and watercolor background gradients.
* **Collapsible Vertical Sidebar**: Toggles between a fully expanded view (`230px`) and a compact icon-only view (`64px`) to maximize workspace real estate.
* **Independent Section Scrolling**: Sticky branding, actions, and theme elements with a scrollable project list.
* **Interactive Views**:
  * 💊 **Program Health**: Overall metrics, progress bar, budget status, quality score, velocity, and open risks count.
  * 🎯 **Focus Areas**: Key focus checklist per sub-project.
  * 📅 **Timeline**: Color-coded past, present, and future activity milestones.
  * ⚠️ **Risks Tracker**: Severe, medium, and low risk registration with mitigation actions.
  * 📊 **Weekly Pulse**: Monday-to-Friday week-by-week wins (green) and blockers (red) log with quick navigations.
* **Light / Dark Theme Switch**: Sleek mode toggle located in the sidebar footer with automatic state saving in `localStorage`.
* **Last Updated Indicator**: Integrated date picker in the sidebar header to track data freshness.
* **Data Lifecycle Sync**:
  * Loads original dataset from [program-tracker-data.json](program-tracker-data.json).
  * Auto-saves changes in `localStorage` to keep edits safe across sessions.
  * Easy JSON import/export options inside the left navigation.

---

## 🛠 Tech Stack

* **Structure & UI**: HTML5, Vanilla CSS3 (custom layouts & transitions), FontAwesome, Bootstrap (Resume page).
* **Interactions & Core Logic**: Vanilla Javascript (ES6).
* **Data Persistence**: JSON-based state layers integrated with `localStorage`.

---

## 📂 Project Structure

```
.
├── README.md                     # This file
├── index.html                    # Resume Landing Page
├── program-tracker.html          # Dynamic Program Tracker Page
├── program-tracker-data.json     # Tracker database file
├── prompts.html                  # AI Prompt engineering log
├── assets/                       # Images, styling templates, and dependencies
└── ...
```

---

## 💻 Local Setup & Development

To view the website locally, launch a local HTTP server:

```bash
# Python 3
python3 -m http.server 8080
```

Then visit:
* Portfolio Website: `http://localhost:8080/index.html`
* Program Tracker: `http://localhost:8080/program-tracker.html`
