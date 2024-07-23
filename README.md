# Process_Monitor
A simple Python application for monitoring system processes, displaying their PID, name, status, and CPU usage in real time.   

## Features  

- Lists all running processes on your machine.  
- Displays the following information for each process:  
  - Process ID (PID)  
  - Process Name  
  - Status (Running, Stopped, etc.)  
  - CPU Usage  
- Refreshes the information every few seconds for real-time monitoring.  

## Requirements  

- Python 3.x  
- `psutil` library (for process management)  
- `PyInstaller` (for creating an executable)  
