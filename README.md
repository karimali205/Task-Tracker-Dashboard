# 🚀 Task Tracker & MIS Operations Portal

> **Enterprise Intelligence Monitoring, Project Queues, and Operations Workflow Portal.**  
> Designed for high-reliability environments (Citrix Virtual Desktops, Terminal Servers, and Modern Web).

---

## 🌟 Key Features

- **📋 Dual Kanban Boards:**
  - **Project Backlog Board:** Personal/departmental task tracking with drag-and-drop.
  - **Assigned Tasks Board:** Multi-tier delegation (UpperAdmin, Admin, Team Members) with real-time status transitions and comment threads.
- **⚖️ Team Workload Balance:** Real-time visibility of active tasks per team member before assigning new work to ensure fair task distribution.
- **⏳ Smart SLA Countdown Badges:** Dynamic visual indicators (`🚨 Overdue`, `⏳ 3h left`, `⚡ Due today`, `📅 In X days`).
- **📝 Meeting Minutes & Action Tracker (Split-Workspace):**
  - Dedicated notebook for meetings with automated bullet-point note taking.
  - Instant one-click task conversion (`Convert to Task ⚡`) directly linking decisions to assigned action items.
  - One-click Outlook integration to dispatch executive meeting minutes to attendees.
- **🔁 Operations Routine Trackers:** Daily, weekly, and monthly recurring checklists with deadline and completion tracking.
- **🛡️ Enterprise Role-Based Access Control (RBAC):**
  - **UpperAdmin:** Complete visibility and governance across all teams and projects.
  - **Admin:** Team management and task assignment scoped strictly to assigned team members (`managedUsers`).
  - **User:** Focused dashboard viewing only their assigned tasks and routines.
- **🔄 Central Multi-User Sync & Automated Backups:** Automatic conflict resolution (smart merge) and 30-day automated rotating backups.
- **🎨 Multi-Theme Support:** Default e& Red, Dark Mode Professional, Corporate Blue, Emerald Green, and Midnight Purple.

---

## 🎮 Live GitHub Interactive Demo

You can try the demo directly in your browser without any server setup:
👉 Open **`Task_Tracker_GitHub_Demo.html`** in any modern web browser.

### 🔑 Demo Accounts

| Role | Username | Password | Permissions |
| :--- | :--- | :--- | :--- |
| **UpperAdmin** | `karim_admin` | `demo123` | Full system access, all boards & all users |
| **Admin (Team Lead)** | `sarah_ops` | `demo123` | Manages Alex, John, and Emma |
| **Team User** | `alex_m` | *(No password)* | Personal assigned tasks & routines |
| **Team User** | `john_d` | *(No password)* | Personal assigned tasks & routines |

---

## 🛠️ Production Deployment (Citrix / Windows LAN)

1. Place `Task_Tracker_Dashboard.html`, `MIS_Backend_Server.ps1`, and `users.csv` in the same directory on a shared network drive or server.
2. Edit `users.csv` to configure your actual team members, roles, passwords, and assigned scopes.
3. Users can launch the application by running **`Run_Task_Tracker.bat`**:
   - Inside **Citrix:** Automatically authenticates the user via their Windows/Citrix session.
   - On **Standard Windows:** Opens the clean system login prompt.

---

## 👨‍💻 Created By

**Karim Ali**  
*Senior MIS Specialist*  
- ✉ **Email:** [karimali12qw@gmail.com](mailto:karimali12qw@gmail.com)  
- 🔗 **LinkedIn:** [Karim Ali](https://www.linkedin.com/in/karim-ali-2209151b6/)  
- 📞 **Phone:** 01116009359  
