# CSCI 4449: Ethical Hacking

Coursework from **CSCI 4449: Ethical Hacking** at the **University of New Haven** (Tagliatela College of Engineering), Spring 2025 (third year, spring semester).

- **Author:** Ryan Godburn
- **Format:** Written reports (PDF)

All testing described in these reports was done against virtual machines and lab networks set up for the course.

## Reports

### Final Project Report (`Final Project Report - Ryan Godburn.pdf`)

*With Ryan Lang · 26 pages*

- **Building vulnerable targets:** set up three VMs on an isolated VMware host-only network (Ubuntu 20.04 and two Windows 7 machines), each deliberately left open to several known CVEs: for example ProFTPD 1.3.3c directory traversal, MoinMoin, weak SSH credentials, Log4Shell, WinRAR, VLC, Internet Explorer, EternalBlue (MS17-010) and a Win32k privilege escalation.
- **Two exploitation rounds:** attacked another set of Windows 7 and Ubuntu machines, documenting each vulnerability (EternalBlue, HTTP.sys, Samba, a WordPress plugin file upload, Webmin, weak SSH and RDP credentials), how it was exploited, and the evidence.

### Kumquat Global Logistics Penetration Test (`Kumquat_Penetration_Test_Report.pdf`)

*Team 3: Ryan Godburn, Nathan Johnson, Emily King, Arielle Nash-Rinaldi · April 2025 · 39 pages*

A professional-style penetration test report for a fictional client, Kumquat Global Logistics (KGL), covering a semester-long assessment of the course's lab network.

- Executive summary, engagement overview and scope.
- Methodology based on the Penetration Testing Execution Standard (PTES) and the OWASP Top 10.
- Eight findings (one critical, five high, two moderate), led by unpatched Windows SMB (MS17-010), default and weak credentials, and poor WordPress access control.
- Risk ratings, evidence, and prioritized remediation recommendations.

---

*Archived coursework, shared as part of my portfolio. If you're taking this course now, please follow your instructor's academic integrity policy.*
