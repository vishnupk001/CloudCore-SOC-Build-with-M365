# CloudCore SOC Build with M365

Architected and automated a secure, cloud-native organization from the ground up using Microsoft 365, Defender, Entra, Intune, and Azure Sentinel.

## Overview

CloudCore SOC Build with M365 is a showcase of my end-to-end design and implementation of a secure, cloud-centric organization using the Microsoft 365 ecosystem. This project demonstrates my ability to plan, deploy, and manage a full-stack security architecture—from tenant setup to a fully integrated Security Operations Center (SOC) with automation.

It reflects hands-on experience with enterprise-grade Microsoft technologies, cloud security best practices, and Infrastructure as Code (IaC) with GitHub and Terraform.

## 🧠 What I Did

### ✅ Domain and M365 Tenant Setup
* Registered a custom domain and connected it to Microsoft 365 via Cloudflare.
* Configured tenant-level settings and verified domain ownership.
### ✅ License Planning and Assignment
* Provisioned Microsoft 365 Business Premium, Defender for Endpoint P2, Defender for Office 365 P2, Entra ID P2, and more.
* Managed licenses through user and group-based assignment in Intune.
### ✅ Identity and Access Management
* Created users and roles with role-based access control (RBAC).
* Configured Conditional Access policies for Entra ID to enforce secure authentication across devices.
### ✅ Device Management & Hardening
* Integrated Autopilot for seamless Windows 11 onboarding.
* Applied CIS benchmark baseline policies via Intune using PowerShell automation.
* Onboarded Android and Windows devices with compliance controls.
### ✅ Threat Protection
* Enabled and configured Microsoft Defender for Office 365 and Defender for Endpoint.
* Applied policy-based protection against phishing, malware, and endpoint threats.
### ✅ SOC Automation with Azure Sentinel
* Created an automated pipeline using GitHub, Terraform, and Azure to deploy:
* Log Analytics Workspace
* Sentinel resources
* Data connectors for Defender, M365, Entra ID, and more
* Configured analytics rules, alerts, and log ingestion from multiple sources.
### ✅ SOAR (Security Orchestration, Automation & Response)
* Built playbooks using Azure Automation Runbooks.
* Automated brute-force attack response by detecting events, creating NSG rules, and sending alert notifications via email.

## 🧰 Technologies Used

| Category          | Tools & Services                                   |
| ----------------- | -------------------------------------------------- |
| Cloud Platform    | Microsoft 365, Azure                               |
| Security          | Microsoft Defender XDR, Intune, Conditional Access |
| Identity          | Entra ID (Azure AD P2), RBAC                       |
| Automation        | Terraform, GitHub, PowerShell, Azure Automation    |
| Monitoring        | Azure Sentinel, Log Analytics                      |
| Device Management | Windows Autopilot, Android Device Management       |


## 💼 Outcome

By completing this project, I demonstrated:

* The ability to architect and automate secure Microsoft 365-based infrastructure.
* Proficiency in integrating security operations, identity management, and endpoint protection.
* Skill in combining manual configuration with Infrastructure as Code for scalable deployment.
* Real-world experience with cloud-native SOC deployment and threat response orchestration.

  

