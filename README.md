# Appy Pie Automate — Dashboard Redesign

A modern, professional redesign of the Appy Pie Automate dashboard. Single-file HTML mockup focused on clarity, hierarchy, and a calm visual language.

## Preview

Open `index.html` directly in any modern browser — no build step, no dependencies beyond Google Fonts (Inter).

Live demo: deployed via Vercel.

## What's inside

- **Sidebar** — Workspace + Account groups, Copilot (AI), Task History, Linked Accounts, MCP, Tools, Help, User Management, and an expandable Folders section with an empty state.
- **Top bar** — Global search, notifications, theme toggle, Upgrade button, avatar.
- **Stats** — KPI tiles for Active Connects, Tasks Completed, Time Saved, Linked Accounts.
- **Hero** — "Create a Quick Automation" gradient card alongside a Usage Overview panel (Connects / Tasks / MCP Servers with progress bars, plan status, Upgrade Plan CTA, and Wallet balance with Add Fund).
- **My Connects table** — Tabs (All / Active / Draft / Paused), app-logo stacks, color-coded status pills, 30-day task counts, last-run timestamps, and inline toggles.
- **Bottom sections** — Recent Activity feed and Popular Templates list.

## Tech

- Plain HTML + CSS (no framework)
- Inter from Google Fonts
- Inline SVG icons
- Responsive: collapses to mobile-friendly layout under 768px

## Structure

```
.
├── index.html   # The full mockup
└── README.md
```

## Deploy

This is a static, single-file site. Deploy to any static host:

- **Vercel** — import the repo at https://vercel.com/new, accept defaults, click Deploy
- **Netlify** — drag the folder onto https://app.netlify.com/drop
- **GitHub Pages** — Settings → Pages → Deploy from `main` / root

## License

MIT — feel free to adapt.
