 Wazuh SIEM Deployment

## Overview

This project demonstrates the deployment and configuration of **Wazuh**, an open-source Security Information and Event Management (SIEM) and Extended Detection and Response (XDR) platform.

The project provided hands-on experience with deploying a SIEM environment, connecting monitored endpoints, analysing security events, investigating alerts, and understanding how endpoint activity is detected and presented within a SOC environment.

The purpose of the project was to strengthen my practical skills in **security monitoring, SIEM administration, threat detection, alert analysis, and incident response**.

---

##  Project Objectives

The main objectives of the deployment were to:

- Deploy and configure a functional Wazuh SIEM environment
- Configure Wazuh agents for endpoint monitoring
- Collect and analyse endpoint security logs
- Monitor security events through the Wazuh dashboard
- Generate and investigate security alerts
- Understand Wazuh rules and alert severity
- Test detection capabilities using simulated security activity
- Develop practical SOC monitoring and investigation skills

---

## Technologies & Tools

| Technology | Purpose |
|---|---|
| **Wazuh** | SIEM, endpoint monitoring and security detection |
| **Linux / Ubuntu** | Hosting and administration of the Wazuh environment |
| **Wazuh Agents** | Endpoint telemetry and security monitoring |
| **Wazuh Dashboard** | Alert monitoring and investigation |
| **Windows** | Monitored endpoint environment |
| **Virtual Machines** | Isolated deployment and testing environment |

---

## Deployment

The project involved deploying the Wazuh environment and configuring endpoints to communicate with the Wazuh server.

Key deployment activities included:

1. Installing and configuring the Wazuh environment.
2. Accessing and configuring the Wazuh dashboard.
3. Deploying Wazuh agents to monitored endpoints.
4. Confirming communication between agents and the Wazuh server.
5. Verifying that endpoint security events were being collected.
6. Monitoring generated alerts through the dashboard.
7. Testing the environment using simulated security activity.

---

## Security Monitoring & Alert Analysis

Once the environment was operational, I used Wazuh to monitor endpoint activity and investigate generated security alerts.

This involved reviewing:

- Alert severity levels
- Endpoint activity
- Authentication and system events
- Security event information
- Wazuh rule information
- Event timestamps
- Source endpoint information
- Detection details

This provided practical experience with the type of **alert triage and investigation workflow used within Security Operations Centres (SOCs).**

---

## Detection Testing

Security activity was generated within the test environment to verify that Wazuh could successfully collect telemetry and generate alerts.

The resulting events were analysed through the Wazuh dashboard to understand:

**Activity → Log Generation → Wazuh Detection → Alert → Investigation**

This helped demonstrate how SIEM platforms transform endpoint activity into actionable information for security analysts.

---

## Wazuh Dashboard

The Wazuh dashboard provided a central location for monitoring connected agents, security events and generated alerts.

The dashboard was used to:

- Verify agent connectivity
- Monitor endpoint events
- Review security alerts
- Analyse alert severity
- Investigate detected activity
- Review security telemetry

---

## Skills Demonstrated

This project demonstrates practical experience in:

- SIEM deployment and configuration
- Wazuh administration
- Security monitoring
- Alert triage
- Log analysis
- Threat detection
- Endpoint monitoring
- Incident investigation
- Linux administration
- Windows security monitoring
- SOC workflows
- Troubleshooting
- Security documentation

---

## Full Deployment Report

A detailed report documenting the deployment, configuration and testing process is included in this repository:

**[Wazuh new deployment.docx](./Wazuh%20new%20deployment.docx)**

The report contains additional information regarding the implementation and testing of the Wazuh environment.

---

## What I Learned

Completing this project improved my understanding of how a SIEM operates within a security monitoring environment.

In particular, I developed a stronger understanding of how endpoint activity generates logs, how those logs are collected and analysed by a SIEM, and how security rules can transform events into alerts that require investigation.

The project also strengthened my practical skills in **SIEM deployment, log analysis, alert investigation, endpoint monitoring and SOC operations**.

---

## Author

**Harrison Tod**

Bachelor of Cyber Security and Behaviour  
Western Sydney University

Cybersecurity interests include:

**Security Operations • Incident Response • Threat Detection • SIEM • Threat Hunting**
