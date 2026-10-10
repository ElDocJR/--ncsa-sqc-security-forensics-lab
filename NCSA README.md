# NCSA SQC | Security Testing and Digital Forensics
**Josh Roybal | NGT Cyber Security Associate Skills Qualification Check**

## Overview
An assessed educational project spanning security testing, packet analysis, memory analysis, and file recovery. The portfolio distinguishes instructor-confirmed results, areas for improvement, and tasks receiving default credit.

## Assessment outcome
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

## Environment
The scored setup includes Kali Linux, Metasploitable 2, Windows 7, and OpenVAS application/OVA. Oracle VirtualBox was the course virtualization platform. The OpenVAS task targeted the Windows VM; the Nmap and FTP-backdoor tasks targeted Metasploitable 2.

## Demonstrated areas
- Service discovery and vulnerability assessment in a training environment.
- Controlled validation of an FTP vulnerability on a deliberately vulnerable lab VM.
- Packet analysis identifying communicating hosts, exposed credentials, the actual transfer port, and transferred data.
- Memory analysis identifying processes, network artifacts, browser history, search artifacts, and hacking-tool evidence.
- Excel file recovery from the provided evidence.

## Evidence and interpretation
The instructor report confirms the Correct task outcomes above. Raw capture/dump/image files, recovered credentials, hashes, and detailed scan outputs are not included. Exact findings cannot be reconstructed from scores alone.

See [LAB-EXPLANATION.md](NCSA-LAB-EXPLANATION.md) for the workflow explanation, assessment feedback, and interpretation limits.

## Improvement areas
Hash cracking and identification of the required NCSA PDF/image content need further practice. The report recommends Hashcat rules with the rockyou dictionary for the hash task. No successful retest is claimed.

## Scope
Educational assessment using course-provided targets and evidence. This is not a professional penetration test or real-world incident response engagement. Public documentation excludes sensitive evidence and restricted assessment answers. Default-credit tasks are not listed as demonstrated skills.

Sources: supplied NCSA SQC instructions and my NCSA score report, displaying September 14, 2026.
[View assessment results (public copy)](evidence_NCSA-SQC-Results.pdf)
