# Network Security Lab: WordPress Brute Force Analysis

## Project Overview
This project involves a deep-dive analysis of network traffic to identify and document a brute force attack against a WordPress installation. The investigation tracks the progression from initial reconnaissance to successful account takeover of the `admin` and `elliot` users.

## Technical Skills Demonstrated
* **Traffic Analysis (PCAP):** Analyzed packet captures to identify the "Hydra" user-agent and high-frequency POST requests.
* **Credential Verification:** Identified successful login attempts by correlating HTTP 302 redirect responses following brute-force patterns.
* **Log Correlation:** Cross-referenced network traffic with system authentication logs to verify unauthorized access.
* **Remediation Planning:** Developed a multi-layered defense strategy including Rate Limiting, 2FA implementation, and account lockout policies.

## Project Contents
* **[Network Traffic Analysis Report](./Network-Traffic-Analysis-Report.pdf):** Formal triage report documenting the scope, impact, and remediation of the attack.
* **[Technical Investigation Notes](./Brute-Force-Technical-Notes.pdf):** Detailed breakdown of TCP streams, packet analysis, and identified Indicators of Compromise (IOCs).
