SOC Lab Report – Entry-Level Analyst Training

Analyst: Peter P. Nguyen
Email: pncybersec@proton.me

Portfolio: TryHackMe Labs

Certifications: CompTIA Security+ (Active)

Date: 02/17/2026
Purpose: Demonstrate applied SOC skills using Splunk to detect, investigate, and alert on simulated threats in a controlled lab environment.

1. PowerShell Monitoring Lab

Scope: Monitored Windows PowerShell execution events to detect potentially malicious commands.

Data Source:

powershell_4688_events.csv

Windows Event ID 4688 (process creation events)

Methodology:

Ingested PowerShell logs into Splunk

Built dashboards to visualize execution patterns

Created correlation searches to flag unusual or suspicious commands

Findings:

Detected abnormal PowerShell executions

Identified potential risk indicators (encoded commands, unexpected hosts, unusual execution times)

Actions / Recommendations:

Alerts were configured for SOC analysts to review and escalate suspicious events

Documented procedures for triaging PowerShell alerts in a Tier-1 SOC environment

2. Brute Force Attack Detection Lab

Scope: Simulated authentication failures to practice detection of credential-based attacks.

Data Source:

bruteforce_auth_events.csv

Windows Event ID 4625 (failed logon attempts)

Methodology:

Created searches for repeated failed logins

Tuned alerts to trigger on thresholds indicating brute force activity

Findings:

Successfully detected simulated password-guessing attempts

Patterns of repeated failed logins across multiple hosts were visualized on dashboards

Actions / Recommendations:

Alerts were generated for analyst investigation

Recommendations included follow-up on targeted accounts and potential password resets

3. Phishing Email Analysis Lab

Scope: Analyze simulated phishing emails to detect social engineering threats.

Data Source:

phishing_attack_logs.csv

Event type: login_attempt

Malicious domains and sender addresses

Methodology:

Examined email headers, links, and attachments

Mapped indicators of compromise (IOCs) to MITRE ATT&CK techniques

Documented workflow for safe investigation

Findings:

Identified suspicious links and attachments

Detected patterns indicative of phishing attempts

Actions / Recommendations:

Recommendations for reporting phishing incidents and escalating potential compromise

Improved processes for end-user awareness and detection

Conclusion

These labs demonstrate applied SOC skills in:

Log ingestion and monitoring

Detection and triage of suspicious activity

Alerting and dashboard creation

Threat analysis using MITRE ATT&CK framework

I am actively seeking an entry-level SOC analyst position, with flexibility for overnight and weekend shifts, to apply and grow these skills in a real-world environment.
