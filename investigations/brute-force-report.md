# Incident Report

## Alert
SSH Brute Force Attack

## Severity
High

## Analysis
A total of 150 failed SSH login attempts were detected from the source IP 192.0.2.45 targeting the admin account on port 22. This activity is consistent with a brute-force attack.

## Key Artifacts

Timestamp: 2023-10-15T02:38:47Z

Source IP: 192.0.2.45

Destination IP: 203.0.113.5

Destination Port: 22

Username: admin

Attempts: 150

Device: Firewall

## MITRE ATT&CK

T1110 - Brute Force

## Verdict

🚨 True Positive

## Recommendation

- Block the source IP.
- Enable Multi-Factor Authentication (MFA).
- Review authentication logs.
- Monitor for further login attempts.
