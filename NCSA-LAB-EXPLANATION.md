# NCSA SQC | Lab Explanation
**Author: Josh Roybal**

## Objective
Demonstrate practical foundations in security testing and digital forensics: observe services, assess weaknesses, interpret network traffic and memory artifacts, and recover relevant files from course evidence.

## Environment
The graded setup includes Kali Linux, Metasploitable 2, Windows 7, and OpenVAS application/OVA in the course VirtualBox environment. The task instructions identify Nmap, airodump-ng, OpenVAS, Metasploit, Hashcat or John the Ripper, and Wireshark. The exact memory-analysis and file-carving tools are not established by the supplied reports and are not asserted here.

## Assessed work
The instructor marked the Nmap scan, local wireless observation, OpenVAS assessment of the Windows VM, and Metasploit FTP-backdoor task against Metasploitable 2 as Correct.

All four packet-analysis answers were marked Correct: involved hosts, credentials, numerical exfiltration port, and transferred data. All five memory-analysis tasks were also marked Correct: process list, network connections, Chrome history, suspicious search terms, and hacking-tool evidence. Excel recovery was marked Correct.

## Verification and evidence
| Area | Evidence supporting a technical explanation | Available confirmation |
| --- | --- | --- |
| Service discovery | Scan logs and identified services | Instructor Correct result |
| Vulnerability assessment | Findings report with supporting evidence | Instructor Correct result |
| FTP validation | Sanitized proof of access on the authorized target | Instructor Correct result |
| Wireless observation | Redacted capture output and adapter details | Instructor Correct result |
| Packet analysis | Frame numbers, TCP streams, connection direction, transferred bytes | Four Correct results |
| Memory analysis | Processes, connection/browser artifacts, correlated observations | Five Correct results |
| Excel recovery | Recovered-file inventory and content validation | Correct result |

The score report validates assessed answers without disclosing their exact technical values. Raw artifacts are not included in this version. Wireless hardware/monitor-mode details and specific commands cannot be inferred from the awarded score.

## Troubleshooting and instructor feedback
The report identifies three areas without credit:
- Hash cracking: the instructor recommends rules with Hashcat and the rockyou dictionary.
- PDF recovery: submitted content did not contain the required NCSA material.
- Image recovery: submitted content did not contain the required NCSA material.

These are assessment findings, not a documented diagnosis of why each attempt failed. Appropriate follow-up is to review the cracking method and validate recovered-file content against the actual task criteria. No completed remediation or successful retest is claimed.

## Results
**Reported outcome: Pass — 930/1,000 points (93%).**

| Assessment area | Result |
| --- | --- |
| Nmap service discovery against Metasploitable 2 | Correct |
| Local wireless observation | Correct |
| OpenVAS assessment of the Windows VM | Correct |
| Metasploit FTP-backdoor task against Metasploitable 2 | Correct |
| Packet analysis: hosts, credentials, transfer port, transferred data | All four Correct |
| Memory analysis: processes, network connections, Chrome history, suspicious searches, hacking-tool evidence | All five Correct |
| Excel file recovery | Correct |
| Hash cracking | No credit; further practice needed |
| Required NCSA PDF/image recovery | No credit; submitted content did not meet the NCSA-content requirement |
| Camera discovery and virus identification | Credit awarded by default; excluded from demonstrated-skill claims |

The report explicitly records Pass and 93%, although a secondary banner says “Not Graded.” The overall outcome above follows the explicit result and scored task rows.

## Lessons and defensive implications
Service discovery, scanner findings, and exploit validation establish different kinds of evidence. An open port does not alone establish exploitability; scanner findings require interpretation. Plaintext credentials in network traffic illustrate the value of encrypted protocols and careful access controls.

FTP control and data flows can use different ports; analysis should establish the actual transfer connection rather than assume port 21. Memory artifacts represent a captured state, and suspicious searches or tool names do not independently prove malicious intent. File carving requires validation of recovered content, not just filenames or extensions.

These are technical interpretations of the project scope, not claims that production defenses were implemented or that a real incident was investigated.

## Source basis and boundaries
Original summary of the supplied NCSA SQC task guide and score report. The scoring report contains virus identification as a default-credit item absent from the supplied instruction guide. Section numbering differs between the two documents; this write-up groups tasks by subject.

Raw evidence could support more detailed case studies, but sensitive browser data, credentials, hashes, wireless identifiers, live camera details, and restricted course assets are excluded from public documentation.
