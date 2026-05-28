# Dung Tran — Vulnerability Management & Security Automation

I use this GitHub as a cybersecurity operations portfolio. The goal is to show how I think through vulnerability management problems, remediation workflows, asset visibility, and security automation.

> **Portfolio status:** This portfolio is still being updated. Projects with blue clickable titles have full repo write-ups available now. Other listed projects are planned or still being cleaned up with sanitized notes, scripts, and documentation.

## Featured Portfolio Projects

### 1. Vulnerability Report Automation
PowerShell-based project for cleaning vulnerability exports, comparing reports, identifying mismatches, and creating easier-to-review remediation reports.
**Skills demonstrated:** PowerShell, Excel reporting, vulnerability data cleanup, remediation support.

### 2. [Enterprise .NET Remediation Case Study](https://github.com/DungTranCyber/enterprise-dotnet-remediation-case-study)

PowerShell case study showing how outdated .NET components were detected, remediated, and validated across Windows endpoints using Intune Proactive Remediations and SCCM/MECM

**Skills demonstrated:** PowerShell, vulnerability remediation, Intune Proactive Remediations, SCCM/MECM, registry detection, x64/x86 handling, safe install-before-uninstall logic, endpoint logging.

### 3. [The No-Error Intune Bug](https://github.com/DungTranCyber/intune-no-error-uninstall-bug)

Case study showing how I troubleshot a silent Intune Win32 app uninstall failure caused by 32-bit PowerShell not reading 64-bit registry uninstall keys.

**Skills demonstrated:** Intune Win32 apps, PowerShell troubleshooting, registry detection, 32-bit vs 64-bit PowerShell, Sysnative, uninstall logic, deployment troubleshooting.

### 4. Risk-Based Vulnerability Prioritization Model
A sample prioritization model using CISA KEV, EPSS, CVSS, VPR, internet exposure, asset criticality, business impact, attack path, and SLA age.
**Skills demonstrated:** modern vulnerability management thinking, risk ranking, business-context prioritization.

### 5. Asset Reconciliation / Owner Mapping Workflow
A project showing how scanner data can be compared against inventory sources to find missing assets, unmanaged systems, duplicate records, and missing owners.
**Skills demonstrated:** asset visibility, owner mapping, remediation routing, Tenable-style operational reporting.

## What This Portfolio Demonstrates

- Turning raw vulnerability data into actionable remediation work
- Prioritizing exploitable business risk instead of only CVSS
- Finding missing, unmanaged, or poorly tagged assets
- Supporting owner-based remediation and SLA tracking
- Using automation and documentation to reduce manual triage
- Connecting technical vulnerabilities to business impact

## Tools & Concepts

**Security:** Tenable VM, Tenable Exposure Management concepts, vulnerability reporting, risk prioritization  
**Prioritization:** CISA KEV, EPSS, CVSS, VPR, asset criticality, exposure, attack path, SLA  
**Automation:** PowerShell, Excel, CSV processing  
**Infrastructure:** Windows Server, Active Directory, Group Policy, Azure, Intune  
**Operations:** asset tagging, owner mapping, ITSM/ticketing workflows, remediation coordination

## Notes

All projects use sample or sanitized data. No real company data, hostnames, IP addresses, credentials, vulnerability exports, tickets, or internal screenshots are included.

## Contact

- LinkedIn: https://www.linkedin.com/in/dungtran1994
- GitHub: https://github.com/DungTranCyber
