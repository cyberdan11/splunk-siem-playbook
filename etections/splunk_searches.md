# Splunk Detections

## Suspicious PowerShell Execution
```spl
index=windows EventCode=4688
| where like(New_Process_Name,"%powershell%")
| stats count by Parent_Process_Name, New_Process_Name
