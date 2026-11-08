# yuva-intern-task-5-security-risk-assessment
YUVA INTERN – TASK 5

Security Risk Assessment & Documentation

Project Type: Cybersecurity | Governance, Risk & Compliance (GRC)
Assessment Platform: Kali Linux
Target Environment: Metasploitable 2
Target IP: 192.168.56.101
Tools: Nmap, Nikto, Searchsploit, NVD
Date: 7 November 2026

---

1. Project Overview

This project presents a security risk assessment of an intentionally vulnerable network environment using Kali Linux and Metasploitable 2.

The primary objective was to identify security weaknesses, evaluate their likelihood and potential business impact, assign risk scores, prioritize security findings, and recommend appropriate mitigation strategies.

The assessment follows a structured risk-based approach to cybersecurity documentation.

2. Objectives

The project addresses all seven objectives of Yuva Intern Task 5:

1. Review network architecture and existing security controls.
2. Identify potential security risks and vulnerabilities.
3. Evaluate the likelihood of identified risks.
4. Assess business and technical impact.
5. Assign appropriate risk levels.
6. Prioritize risks based on severity.
7. Recommend security controls and mitigation measures.

3. Tools & Technologies

Tool| Purpose
Kali Linux| Security assessment environment
Nmap| Network discovery and service enumeration
Nikto| Web server vulnerability scanning
Searchsploit| Public exploit research
NVD| CVE research and vulnerability validation
Metasploitable 2| Intentionally vulnerable lab target

4. Assessment Methodology

The assessment was conducted through the following stages:

- Network architecture and security control review.
- Service and version identification.
- Vulnerability research and evidence collection.
- Likelihood and impact evaluation.
- Risk scoring using a 5 × 5 risk matrix.
- Risk prioritization.
- Security recommendations and remediation planning.

Risk Formula:

Risk Score = Likelihood × Impact

5. Key Findings

The report evaluates 14 security risk entries.

Severity| Findings
Critical| 6
High| 4
Medium| 2
Low| 2

Major findings documented include:

- vsftpd 2.3.4 backdoor vulnerability.
- Samba 3.0.20 security weakness.
- UnrealIRCd 3.2.8.1 backdoor.
- Weak and default credentials.
- Insecure remote access services.
- Outdated software and exposed web applications.
- Insufficient security monitoring.

Some findings remain provisional because their complete original scan output was not included in the supplied evidence.

6. Evidence & Screenshots

The "Screenshots" directory contains available assessment evidence, including:

- Nmap vulnerability scan results.
- Nikto web server scan output.
- Searchsploit vulnerability research.
- NVD CVE references.

The report distinguishes directly observed evidence from findings requiring further validation.

7. Risk Assessment & Mitigation

The assessment recommends:

- Removing vulnerable and backdoored services.
- Updating unsupported software.
- Replacing default credentials.
- Restricting unnecessary network services.
- Implementing firewall rules and network segmentation.
- Replacing insecure protocols with encrypted alternatives.
- Introducing centralized logging and intrusion detection.

8. Project Deliverables

- Security Risk Assessment Report.
- Risk identification and evaluation.
- Likelihood and impact analysis.
- Risk classification and prioritization.
- Recommended security controls.
- Supporting screenshots and vulnerability references.

9. Scope & Disclaimer

This project was conducted for educational purposes in an isolated virtual lab environment using an intentionally vulnerable Metasploitable 2 machine.

All testing was restricted to the authorized lab environment.

This documentation does not represent a production network security audit or certification.

---

Prepared as part of Yuva Intern – Task 5: Security Report & Documentation.
