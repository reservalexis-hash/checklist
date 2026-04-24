# 🔧 Maintenance Checklist

A property maintenance tracking app built with React, Tailwind CSS, and localStorage — all in a single HTML file. No build tools or installs required.

## Features

- **Checklist view** — Track maintenance tasks by unit, section, and filter size
- **History page** — Browse past monthly checklists
- **Manage Units** — Add, edit, or deactivate units
- **Reports page** — View completion stats and download HTML or CSV reports
- **Dark / Light mode** — Toggle between themes with the 🌙 / ☀️ button in the navbar; preference is saved automatically
- **Persistent data** — All data is stored in the browser via localStorage, so nothing is lost on refresh

## How to Use

1. Download or clone this repository
2. Open `index.html` directly in any modern web browser — no server needed
3. Add your units in the **Manage Units** tab
4. Use the **Checklist** tab each month to mark off completed tasks
5. View summaries and export reports from the **Reports** tab

## Tech Stack

- [React 18](https://react.dev/) (loaded via CDN)
- [Tailwind CSS 2](https://tailwindcss.com/) (loaded via CDN)
- [Babel Standalone](https://babeljs.io/) for in-browser JSX transpilation
- Browser `localStorage` for data persistence

## File Structure

```
checklist/
└── index.html   ← entire app in one file
```

## Live Demo

You can view the raw file at:
`https://github.com/reservalexis-hash/checklist/blob/main/index.html`

To run it as a live webpage, enable **GitHub Pages** in the repository Settings → Pages → select the `main` branch.

## License

MIT — free to use and modify.
