# PM Productivity – Command Center

A single place to **monitor team progress**, work with **Azure DevOps** and **GitHub**, and stay on top of delivery. Use this repo from Cursor with MCP (Azure DevOps + GitHub) for an efficient product manager workflow.

---

## What's in this repo

| Area | Purpose |
|------|--------|
| **Morning reports** | Daily snapshot: your assigned work, items needing attention, current iteration (Azure DevOps). |
| **Docs & analysis** | RFP responses, requirement notes, process/risk docs, and ad‑hoc analysis. |
| **Scripts** | Generate reports, run analyses, batch processing (e.g. PFR, impacted modules). |
| **Wiki MCP server** | Optional MCP server for your internal wiki – see [QUICKSTART.md](QUICKSTART.md). |

---

## Quick start

1. **Connect this folder to GitHub**  
   See [PROJECT_SETUP.md](PROJECT_SETUP.md) for adding the remote and first push to **https://github.com/mortenwj/pm-productivity**.

2. **Daily workflow**  
   See [DAILY_WORKFLOW.md](DAILY_WORKFLOW.md) for:
   - Morning report (Azure DevOps: your work, iteration, backlogs)
   - GitHub: issues, PRs, repos
   - Staying on top without context-switching

3. **Generate a morning report**  
   In Cursor, say e.g. *"Good morning"* or *"Generate my morning report"* (with Azure DevOps MCP configured). Output: `morning_report_YYYY-MM-DD.md`.

---

## Recommended setup

- **Cursor** as your main workspace.
- **MCP servers**: Azure DevOps (work items, backlogs, iterations, capacity) and GitHub (issues, PRs, repos).
- **This repo** as the single project for PM artifacts: reports, notes, and scripts.

---

## Repo layout (overview)

```
├── README.md                 ← You are here
├── PROJECT_SETUP.md          ← GitHub remote + first push
├── DAILY_WORKFLOW.md         ← DevOps + GitHub daily routine
├── morning_report_*.md       ← Generated morning reports
├── generate_morning_report.py
├── QUICKSTART.md             ← Wiki MCP server (optional)
├── server.py                 ← Wiki MCP server (optional)
└── ... (other scripts and docs)
```

---

## Wiki MCP server (optional)

This repo also includes a small MCP server for connecting to an internal wiki (MediaWiki, Confluence, Wiki.js). Configuration and usage: [QUICKSTART.md](QUICKSTART.md).
