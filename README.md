# 🔧 HighPressure Labs: Linux & Cloud Handbook

Welcome to **HighPressure Labs**! This repository is a hands-on engineering log, cheat sheet collection, and lab tracker for mastering Linux systems, networking, and cloud administration.

## 🗂️ Repository Structure
* **`labs/`** — Post-mortem write-ups and mission logs for completed lab tickets.
* **`scripts/`** — Bash scripts, automation tools, and cron jobs.
* **`cheatsheets/`** — Quick-reference guides written in plain English.

## 🔄 The Lab Workflow (How to Complete a Mission)
1. **Pick a Ticket:** Move an issue from **Up Next** to **In Progress** on the Project board.
2. **Do the Work:** SSH into the lab VM and complete the mission objectives.
3. **Document the Artifact:** Create a short Markdown note in `labs/` or update a file in `cheatsheets/` with the commands you used.
4. **Ship It:**
   ```bash
   git status
   git add .
   git commit -m "Complete lab mission (Fixes #<issue-number>)"
   git push

```

