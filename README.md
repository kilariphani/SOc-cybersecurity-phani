1. Brute Force Attack Detection
Simulated multiple failed login attempts on Windows/Linux system
SIEM collected authentication logs
Detection rule triggered after multiple failures in short time
Alert generated: Possible Brute Force Attack
 2. Suspicious Login Detection
Simulated login from unknown IP / different location
SIEM analyzed geo-location and IP behavior
Alert generated: Anomalous Login Detected
 3. Malware Execution Detection
Executed test malware file (EICAR test file)
Endpoint logs captured file execution event
SIEM matched with threat intelligence database
Alert generated: Malicious File Detected
 4. Data Exfiltration Detection
Simulated large file transfer to external system
SIEM monitored outbound network traffic
Unusual data transfer identified
Alert generated: Possible Data Exfiltration
 5. Privilege Escalation Detection
Simulated user privilege change to admin/root access
System logs captured privilege change event
SIEM detected abnormal access behavior
Alert generated: Privilege Escalation Attempt
