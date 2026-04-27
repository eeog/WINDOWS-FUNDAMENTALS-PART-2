# Windows Fundamentals Part 2 — Case Study

## Objective
To investigate Windows configuration tools and system utilities to understand system behaviour, security posture, and potential investigation points.

## Key Findings

### System Configuration
- Standard startup behaviour  
- No suspicious services  
- Startup items empty due to Windows Server design  

### UAC
- Default “Notify for apps” level  
- Secure Desktop enabled  

### Computer Management
- No suspicious scheduled tasks  
- Event Viewer logs normal  
- No unauthorized shares  
- No active sessions  

### System Information
- Hardware and software environment consistent with VM defaults  

### Resource Monitor
- Normal CPU, memory, disk, and network activity  

### Command Prompt
- Network configuration retrieved  
- Active connections reviewed  
- No suspicious netstat entries  

### Registry
- No unauthorized modifications detected  

## Conclusion
The system appears to be configured with standard Windows Server defaults.  
No malicious activity or misconfigurations were identified.

This project demonstrates:

- Windows endpoint investigation  
- System configuration analysis  
- SOC‑aligned documentation  
- Command‑line proficiency  
