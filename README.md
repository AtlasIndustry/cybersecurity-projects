# 🛡️ Cybersecurity Projects

This repository contains a curated collection of my cybersecurity projects spanning red teaming, blue teaming, cloud deployments, scripting, infrastructure simulation, and security automation. Each project highlights specific skills, technologies, and outcomes relevant to enterprise and offensive security use cases.

---

## 📚 Project Index

1. [Red Team Infrastructure Deployment – Phishing & C2 Framework](#1-red-team-infrastructure-deployment--phishing--c2-framework)  
2. [Enterprise Network Simulation – Multi-Firewall and Monitoring Lab](#2-enterprise-network-simulation--multi-firewall-and-monitoring-lab)  
3. [AWS Architecture & Deployment Projects (Course Completion)](#3-aws-architecture--deployment-projects-course-completion)  
4. [Network Traffic & Endpoint Monitoring – Lab and Incident Report Writing](#4-network-traffic--endpoint-monitoring--lab-and-incident-report-writing)  
5. [Web Application & Network Penetration Testing with Cisco Infrastructure](#5-web-application--network-penetration-testing-with-cisco-infrastructure)  
6. [Identity & Access Management (IAM) Architecture and Consulting Project](#6-identity--access-management-iam-architecture-and-consulting-project)  
7. [Scripting & Automation Projects – PowerShell, Python, and Java](#7-scripting--automation-projects--powershell-python-and-java)  
8. [Lead Tracking & Sales Automation System](#8-lead-tracking--sales-automation-system)  
9. [Secure Routing & Network Segmentation Lab (Cisco Packet Tracer)](#9-secure-routing--network-segmentation-lab-cisco-packet-tracer)

---

## 1. Red Team Infrastructure Deployment – Phishing & C2 Framework

**Goal:** Build and test a full red team infrastructure simulating real-world phishing and post-exploitation techniques  
**Tools/Tech:** Evilginx2, Ubuntu 22.04, AWS EC2, Route 53, Apache2, Let’s Encrypt, Namecheap, Mythic C2, Athena payload, SSH tunneling, Visual Studio, C#

**Actions:**
- Deployed an Evilginx2 phishing framework on an AWS EC2 instance
- Registered domain, configured DNS in Route 53, and implemented SSL/TLS using Let’s Encrypt
- Created a realistic phishing site mimicking Google login with custom HTML/CSS and PHP
- Built and tested a Mythic C2 server with a custom Athena payload and verified live callbacks from a Windows VM
- Developed a lightweight C# executable for system reconnaissance and log generation
- Implemented SSH tunneling to securely route command-and-control traffic during testing
- Documented the full deployment and submitted to a red team manager for review

**Outcome:** Successfully captured credentials/session tokens and received working callbacks; developed a deep understanding of phishing infrastructure, TLS/SSL, C2 frameworks, Windows payloads, SSH tunneling, and AWS services

---

## 2. Enterprise Network Simulation – Multi-Firewall and Monitoring Lab

**Goal:** Simulate an enterprise network with layered defense, monitoring, and attack detection  
**Tools/Tech:** Palo Alto, Fortigate, IIS, RADIUS, DUO, Splunk, Security Onion, Kali Linux, Burp Suite, Nmap, Squid

**Actions:**
- Set up external (Palo Alto) and internal (Fortigate) firewalls with full route, rule, and VLAN segmentation
- Configured VPN access via Palo Alto and integrated multi-factor authentication using DUO and RADIUS
- Installed and configured multiple IIS webservers across different subnets
- Launched internal penetration test by pivoting through vulnerable systems into protected networks
- Collected endpoint and network telemetry via Splunk and Security Onion
- Wrote and deployed a custom detection rule in Security Onion to trigger on suspicious internal activity
- Built and configured a Squid proxy server to enforce access control and monitor outbound web traffic

**Outcome:** Gained end-to-end experience with segmentation, secure remote access, lateral movement, and network visibility. Lab successfully detected simulated attack behaviors

---

## 3. AWS Architecture & Deployment Projects (Course Completion)

**Goal:** Complete real-world AWS deployments for cloud services, architecture design, and infrastructure-as-code  
**Tools/Tech:** AWS EC2, S3, RDS, VPC, IAM, CloudFormation, Load Balancers, Route 53, CloudWatch

**Actions:**
- Designed and launched a fault-tolerant web application using Auto Scaling Groups and Elastic Load Balancing
- Created secure, segmented VPCs with custom subnets, NAT gateways, and routing tables
- Implemented IAM policies and roles for least-privilege access control
- Configured static hosting on S3 with Route 53 DNS and CloudFront for performance and security
- Used CloudFormation to deploy reusable infrastructure templates

**Outcome:** Completed all hands-on projects from the AWS Solutions Architect Associate training course; gained practical fluency with core AWS services and deployment workflows

---

## 4. Network Traffic & Endpoint Monitoring – Lab and Incident Report Writing

**Goal:** Gain hands-on experience analyzing network traffic, endpoint logs, and writing professional investigation reports  
**Tools/Tech:** Wireshark, tcpdump, Sysmon, Security Onion, Windows Event Viewer

**Actions:**
- Used Wireshark and tcpdump in lab exercises to analyze packet captures and identify potential malicious behavior
- Installed and configured Sysmon on Windows endpoints to enrich event logging and provide high-fidelity telemetry
- Examined Windows event logs to identify artifacts related to malware execution and lateral movement
- Conducted midterm and final investigations using Security Onion logs
- Wrote and submitted full incident reports detailing observed malicious behavior, root cause, and mitigation steps

**Outcome:** Developed practical skills in traffic analysis, endpoint monitoring, and cybersecurity reporting; improved analytical thinking and report writing under real-world scenarios

---

## 5. Web Application & Network Penetration Testing with Cisco Infrastructure

**Goal:** Conduct web and network penetration testing exercises within a simulated architecture using Cisco devices  
**Tools/Tech:** Cisco routers/switches, Burp Suite, Kali Linux, Nmap, custom mock architecture

**Actions:**
- Participated in a team-based penetration test targeting a lab-built web application and supporting infrastructure
- Performed vulnerability scanning, enumeration, and exploitation using Nmap, Burp Suite, and other tools
- Evaluated architecture security posture including Cisco router configurations and access control implementations
- Created and delivered a full security presentation reporting findings, risks, and recommended mitigations

**Outcome:** Gained real-world practice in end-to-end testing and reporting; strengthened skills in web attack techniques, network exploitation, and communication of technical results

---

## 6. Identity & Access Management (IAM) Architecture and Consulting Project

**Goal:** Simulate an IAM consulting engagement for a mock company seeking modernization of its access control infrastructure  
**Tools/Tech:** OAuth2, SAML, CAS, IAM frameworks, policy documentation

**Actions:**
- Set up and configured an OAuth2 authorization server and a SAML identity provider with a CAS server for SSO
- Acted as a mock IAM consulting team for the course final project
- Developed and delivered a full modernization proposal including:
  - IAM governance documentation  
  - Statement of Work (SOW)  
  - IAM solution architecture diagram  
  - "Low-hanging fruit" security improvement plan

**Outcome:** Gained hands-on experience with enterprise IAM protocols and architecture design; improved client-facing communication and documentation skills

---

## 7. Scripting & Automation Projects – PowerShell, Python, and Java

**Goal:** Automate key cybersecurity tasks and infrastructure management using scripting languages  
**Tools/Tech:** PowerShell, Python, Java, Docker, Windows, Linux

**Actions:**
- Built PowerShell scripts to scan networks, identify misconfigurations, and automate recon tasks
- Wrote Python tools for parsing scan data, managing security workflows, and integrating with red team tools
- Used Java to develop helper programs for containerized testing environments via Docker
- Created reusable automation scripts for system setup, security checks, and rapid test deployment

**Outcome:** Improved fluency in practical scripting; gained experience in automation and tooling development to streamline both offensive and administrative security tasks

---

## 8. Lead Tracking & Sales Automation System

**Goal:** Build a scalable lead tracking and automation workflow with future integration of APIs and custom scripting  
**Tools/Tech:** Zapier, HubSpot, Google Sheets, GitHub

**Actions:**
- Designed and implemented a Zapier-based workflow to route inbound lead data into HubSpot
- Built a Google Sheets dashboard to visualize, organize, and track lead information
- Created a GitHub repository to document architecture, logic flow, and planned technical enhancements
- Outlined future integration of APIs and Google Apps Script to automate enrichment and system expansion

**Outcome:** Laid the groundwork for a low-code, extensible sales automation system; improved workflow design, data organization, and automation planning capabilities

---

## 9. Secure Routing & Network Segmentation Lab (Cisco Packet Tracer)

**Goal:** Design and simulate a segmented enterprise network with inter-VLAN routing, access control lists, and dynamic routing protocols  
**Tools/Tech:** Cisco Packet Tracer, VLANs, OSPF, EIGRP, ACLs, Layer 3 Switching

**Actions:**
- Created a multi-subnet network with VLAN segmentation across departments (e.g., HR, Finance, IT)
- Configured inter-VLAN routing using a Layer 3 switch
- Implemented OSPF and EIGRP and verified redistribution between protocols
- Applied standard and extended ACLs to restrict traffic between VLANs based on business logic
- Tested routing functionality, failover behavior, and access restrictions
- Documented full network topology, configurations, and routing tables

**Outcome:** Demonstrated core networking skills including segmentation, access control, and routing protocol configuration; built a strong foundation in secure network architecture using Cisco best practices
