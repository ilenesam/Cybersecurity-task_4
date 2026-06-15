Cybersecurity-task_4
Task 4 - Setup and Use a Firewall on Windows

Objective
Configure and test basic firewall rules to allow or block traffic.

 Tool Used
Windows Defender Firewall with Advanced Security

 Steps Performed

1. Opened Windows Defender Firewall.
2. Viewed existing inbound firewall rules.
3. Created a new inbound rule to block TCP Port 23 (Telnet).
4. Verified the rule was successfully added.
5. Tested the configuration using Command Prompt.
6. Removed the test rule to restore the original configuration.

Screenshots Included

- Existing Firewall Rules
- Block Port 23 Rule Creation
- Rule Successfully Added
- Command Prompt Verification
- Rule Removal

Why Block Port 23?

Port 23 is used by Telnet, which sends data in plain text and is considered insecure. Blocking it helps prevent unauthorized access and protects network communications.

Conclusion

This task demonstrated basic firewall management by creating, testing, and removing firewall rules. Firewalls help filter network traffic and improve system security.
