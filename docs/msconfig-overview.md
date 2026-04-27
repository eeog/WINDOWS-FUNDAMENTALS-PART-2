# System Configuration (msconfig)

The System Configuration utility is used for advanced troubleshooting and startup diagnostics. It contains five tabs:

- General  
- Boot  
- Services  
- Startup  
- Tools  

## General Tab
Controls startup behaviour:
- Normal startup  
- Diagnostic startup  
- Selective startup  

## Boot Tab
Controls OS boot options:
- Safe boot  
- Boot logging  
- Base video  
- Timeout settings  

## Services Tab
Lists all system services (running or stopped).  
Useful for identifying disabled, suspicious, or malfunctioning services.

## Startup Tab (Windows Server)
Windows Server does not show startup items in Task Manager or msconfig.  
Startup items must be checked via:

```
Win + R → shell:startup
```

## Tools Tab
Provides quick access to administrative utilities such as:
- Event Viewer  
- System Information  
- Registry Editor  
- Performance Monitor  
- Resource Monitor  
