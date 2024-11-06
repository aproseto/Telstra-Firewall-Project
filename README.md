# Telstra Firewall Project

## Objective

The Telstra Firewall Project is a learning program designed by Telstra's Security Operations Center to gain hands-on experience of responsibilities of a Security Analyst at their company. This project aimed to triage a zero-day vulnerability malware attack (CVE-2022-22965) known as Spring4Shell and contact the team that is most affected. Then I will analyze the malware data and information, implement a new firewall rule with the Python coding language to mitigate the malware's damage, and draft an incident post-mortem of the malware attack.

### Skills Learned

- Exercise on Python coding for firewall rules.
- Formal report write-up of incident post-mortem.

### Tools Used

- Python 3.13 using IDLE editor.
- Microsoft Word


## Task 1: Email to Impacted Team
![Task 1 Response](https://github.com/user-attachments/assets/b33517ec-b344-46ec-a65a-36cfc56f845f)

*Ref 1: Email send to team that had critical severity impact*

## Firewall Rule
![Task 2 Before](https://github.com/user-attachments/assets/97ed3281-7cf9-4021-8a2b-f23139555904)

*Ref 2: Pre firewall rule*

<br/>![Task 2 Code](https://github.com/user-attachments/assets/7b863a3a-b49f-49cb-bd36-f3abb4c5bfa3)

*Ref 3: Python code to implement firewall rule*

<br/>![Task 2 After](https://github.com/user-attachments/assets/fcf292be-19e6-458a-8aa0-661f26b5cff6)

*Ref 4: Post firewall rule which rejected the malware*

## Incident Post-mortem
![Task 3](https://github.com/user-attachments/assets/a48c6a52-bfb0-46fd-9e92-d6cd11b9bc4e)
![Task 3-1](https://github.com/user-attachments/assets/de0a7ce7-bba1-411b-a4bf-541e66680a2e)

*Ref 5: Incident Report*

### Resources Used
- https://github.com/craig/SpringCore0day/blob/main/exp.py
- https://docs.python.org/3/library/http.server.html
- https://spring.io/security/cve-2022-22965
- https://www.cisa.gov/news-events/alerts/2022/04/01/spring-releases-security-updates-addressing-spring4shell-and-spring
