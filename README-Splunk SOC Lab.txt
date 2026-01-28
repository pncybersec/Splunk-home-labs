Splunk SOC Lab

I built these labs to learn real SOC skills. They show how I use Splunk to find and stop attacks.
What's Here
1. PowerShell Monitoring Lab

Spl: source="powershell_4688_events.csv" host="*" sourcetype="csv"
Could also search for 4688 with "powershell"
    Tracked PowerShell execution on Windows

    Made dashboards to spot suspicious activity

    Set up alerts for SOC analysts

2. Brute Force Attack Detection

Spl:source="bruteforce_auth_events.csv" host="*" sourcetype="csv" (status="failure" OR fail)
Could also search for windows Event 4625
    Simulated password guessing attacks

    Built searches to find attack patterns

    Created alerts for too many failed logins

3. Phishing Email Analysis
source="phishing_attack_logs.csv" host="*" sourcetype="csv" event_type="login_attempt"
Could also search for the malicious domain

    Analyzed fake phishing emails in a safe lab

    Looked for suspicious links and attachments

    Learned how to spot social engineering tricks

Let's Connect

I'm actively seeking an entry-level SOC analyst position, especially in overnight or shift roles where I can grow and contribute from day one.

Email: pncybersec@proton.me
Portfolio: TryHackMe
Certs: CompTIA Security+