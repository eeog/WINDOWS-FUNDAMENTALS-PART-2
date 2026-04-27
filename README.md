# Windows Fundamentals Part 2 — System Configuration & Endpoint Analysis

This project documents a full investigation of Windows configuration tools, system utilities, and command‑line diagnostics. It demonstrates practical endpoint analysis skills relevant to SOC analysts, incident responders, and IT security professionals.

The investigation covers:

- System Configuration (msconfig)
- User Account Control (UAC)
- Computer Management (compmgmt.msc)
- Task Scheduler
- Event Viewer
- Shared Folders
- Local Users & Groups
- Performance Monitor (perfmon)
- Device Manager
- Disk Management
- Services & Applications
- WMI Control
- System Information (msinfo32)
- Resource Monitor (resmon)
- Command Prompt (cmd.exe)
- Windows Registry (regedit)

All findings are documented in a SOC‑aligned format with clear explanations, evidence references, and security relevance.

---

# 📂 Repository Structure

```
Windows-Fundamentals-Part-2/
│
├── README.md
├── case-study.md
│
├── docs/
│   ├── msconfig-overview.md
│   ├── uac-settings.md
│   ├── computer-management.md
│   ├── task-scheduler.md
│   ├── event-viewer.md
│   ├── shared-folders.md
│   ├── performance-monitor.md
│   ├── device-manager.md
│   ├── disk-management.md
│   ├── services-and-applications.md
│   ├── wmi-control.md
│   ├── msinfo32-overview.md
│   ├── environment-variables.md
│   ├── resource-monitor.md
│   ├── command-prompt-basics.md
│   ├── networking-commands.md
│   └── windows-registry.md
│
└── evidence/
    ├── msconfig-general.txt
    ├── msconfig-boot.txt
    ├── msconfig-services.txt
    ├── startup-folder.txt
    ├── uac-level.txt
    ├── task-scheduler.txt
    ├── event-viewer.txt
    ├── shared-folders.txt
    ├── perfmon.txt
    ├── device-manager.txt
    ├── disk-management.txt
    ├── services.txt
    ├── wmi.txt
    ├── msinfo32.txt
    ├── environment-variables.txt
    ├── resmon.txt
    ├── hostname.txt
    ├── whoami.txt
    ├── ipconfig.txt
    ├── netstat.txt
    └── registry.txt
```

---

# 🧠 Skills Demonstrated

- Windows endpoint investigation  
- System configuration analysis  
- Service enumeration  
- Startup program analysis  
- Network diagnostics  
- Command‑line investigation  
- Virtual memory & crash dump analysis  
- Registry awareness  
- SOC‑style documentation discipline  

---

# 📄 Documentation

All documentation is located in the `docs/` folder.  
Each file contains:

- Tool purpose  
- How it was accessed  
- What was analysed  
- Security relevance  
- Evidence references  

---

# 📘 Case Study

See `case-study.md` for a full narrative investigation report.
