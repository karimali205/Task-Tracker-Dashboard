# Task Tracker Dashboard (Live Demo)

A lightweight team task-management tool (Kanban + routines) built with plain HTML, CSS and JavaScript — no frameworks, no installation.

**Live demo:** https://YOUR-USERNAME.github.io/YOUR-REPO/

## Try it
| Role | Username | Password |
|------|----------|----------|
| User | `alex` | — |
| Admin (Team A) | `demo_admin` | `demo123` |
| Upper Admin | `demo_upper` | `demo123` |

Tip: log in as `demo_admin`, comment/assign a task, log out, then log in as `alex` to see the other side of the workflow.

> Demo data is stored **only in your own browser** (nothing is sent anywhere). Use "Reset demo data" on the login screen to start over.

## Features
- Role-based access: User / Admin / Upper Admin, with each admin managing only their own team
- Project Backlog + Assigned Tasks Kanban boards with drag & drop (and checkboxes)
- Priority, labels, deadlines, overdue highlighting, search and filters (member / priority / deadline)
- Edit & re-assign tasks, Outlook email drafts for assignments and reminders
- Comment threads per task with unread notifications (🔔)
- Daily / Weekly / Monthly routines that reset automatically
- Export to CSV (each admin exports only their own data)
- 5 color themes

## Real deployment
The production version runs against a small PowerShell server that stores everything in a shared JSON file (multi-user, auto-refresh every 15 seconds). Set `DEMO_MODE = false` at the top of the HTML to use it.
