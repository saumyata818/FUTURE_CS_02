# SIEM-Based Incident Monitoring and Analysis

## Project Overview

This project simulates real-world security event monitoring using **Splunk SIEM**. The primary goal was to analyze structured log data to detect suspicious activities such as failed logins, brute-force attempts, malware infections, and user-IP anomalies.

## Tools Used

- **SIEM Tool:** Splunk (Free Trial)
- **Log Source:** Custom Sample Log File (`SOC_Task2_Sample_Logs.txt`)
- **Analysis Environment:** Splunk Web Interface & Search Processing Language (SPL)

---

## Steps Performed

1. **Splunk Setup**
   - Created a Splunk account and accessed the dashboard.
   - Selected required Windows event logs (Application, Security, System) for monitoring.
   - Uploaded the sample log file through Splunk's upload interface.
   - Verified log ingestion by running a wildcard search (`*`), retrieving over **107,000 events**.

2. **Log Analysis with SPL Queries**
   - Identified failed login attempts to detect suspicious login patterns.
   - Queried successful logins for correlation with failed attempts.
   - Extracted frequent login failures by user and IP to identify brute-force attack sources.
   - Correlated failed and successful login events to highlight possible credential compromises.
   - Analyzed malware detection logs linked with users and IPs.
   
3. **Incident Analysis**
   - Investigated brute-force attempts, account compromise patterns, and malware infections.
   - Mapped incidents with severity levels and prepared recommendations.

4. **Security Recommendations**
   - Immediate actions: IP blocking, user password resets, and isolation of infected devices.
   - Preventive measures: Enabling MFA, login rate limiting, and periodic auditing.
   - Continuous review and awareness training.

5. **Incident Communication**
   - Prepared and shared an incident report email summarizing key findings and suggested actions.

---

## Learning Outcomes

- Hands-on experience with Splunk’s log analysis and search queries.
- Identified attack patterns including brute-force, malware infections, and credential compromise.
- Understood the importance of correlating login events with malware activity.
- Developed an incident communication workflow.

---

## Disclaimer
> This project was conducted in a controlled environment with simulated data for educational purposes. No real-world systems or sensitive information were used or impacted.

---

## Author

**Saumyata Nepal**  
Intern – Future Interns Program  
Date: July 2025

---

## Contact

For any queries or collaboration, feel free to reach out! via my linkedin: https://www.linkedin.com/in/saumyata-nepal-1818a5312/
