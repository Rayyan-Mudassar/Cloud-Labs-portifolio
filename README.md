
# ☁️ Rayyan Mudassar — Cloud Portfolio

> Aspiring Cloud & Security Engineer | AWS | Azure | Linux | Networking | IAM Security

[![Azure](https://img.shields.io/badge/Azure-AZ--104%20Ready-0078D4?style=flat&logo=microsoftazure)](https://azure.microsoft.com)
[![AWS](https://img.shields.io/badge/AWS-SAA%20In%20Progress-FF9900?style=flat&logo=amazonaws)](https://aws.amazon.com)
[![Security](https://img.shields.io/badge/ISC2-CC%20Candidate-4CAF50?style=flat)](https://www.isc2.org)

---

## 👋 About Me

I am a cloud practitioner with hands-on experience across **AWS and Azure**, focused on building secure, highly available, and scalable cloud infrastructure. My background spans cloud administration, identity & access management, network security, and infrastructure automation.

- 🎯 **Goal:** Land a role in Cloud Engineering or Cloud Security
- 📜 **Certifications:** AZ-104 (Practice Assessment Passed) | AWS SAA (In Progress) | ISC2 CC (April 2026)
- 🛠️ **Skills:** AWS, Azure, Linux, Bash Scripting, Nginx, IAM, Networking, GitHub Actions, CI/CD

---

## 🗂️ Projects

### 🔐 1. Azure Key Vault — Secure App Service with Managed Identity
**Cloud:** Azure | **Focus:** Security, IAM, Secrets Management

Implemented a zero-trust secrets management solution by storing sensitive credentials (passwords, connection strings) in **Azure Key Vault** and granting an **App Service** access via **Managed Identity** — eliminating hardcoded credentials entirely from the application code.

**What I did:**
- Created and stored secrets securely in Azure Key Vault
- Enabled System-Assigned Managed Identity on App Service
- Configured Key Vault access policies to allow the App Service to retrieve secrets at runtime
- Eliminated credential exposure risk by removing all hardcoded secrets

**Skills demonstrated:** Azure Key Vault, Managed Identity, App Service, IAM, Security Best Practices

---

### ⚖️ 2. High Availability Web Deployment with AWS Load Balancer
**Cloud:** AWS | **Focus:** High Availability, EC2, Load Balancing

Designed and deployed a fault-tolerant web hosting architecture using two EC2 instances behind an **Application Load Balancer (ALB)**, ensuring zero downtime if one instance fails.

**What I did:**
- Launched 2 EC2 instances hosting identical web application
- Configured an Application Load Balancer to distribute traffic across both instances
- Tested failover scenario — confirmed website remained accessible when one EC2 was stopped
- Configured health checks so ALB automatically routes away from unhealthy instances

**Skills demonstrated:** EC2, Application Load Balancer, High Availability, Health Checks, AWS Networking

---

### 📊 3. SaaS Monitoring System with AWS EC2 + Nginx
**Cloud:** AWS | **Focus:** Monitoring, Automation, Python, Nginx

Built and deployed a real-time website monitoring tool that tracks **uptime and SSL certificate expiration**, sending automated email alerts when issues are detected — hosted publicly on EC2 using Nginx as a reverse proxy.

**What I did:**
- Wrote a Python monitoring script that checks website uptime and SSL expiry
- Configured automated email alerts triggered when a site goes down or SSL nears expiration
- Deployed the monitoring dashboard on EC2 with **Nginx** as a reverse proxy for public access
- Ensured 24/7 availability of the monitoring service on the cloud

**Skills demonstrated:** Python, AWS EC2, Nginx, SSL/TLS, Monitoring & Alerting, Automation

---

### 🚀 4. Node.js App Deployment with GitHub Actions + Managed Identity
**Cloud:** Azure | **Focus:** CI/CD, DevOps, IAM, Blob Storage

Automated the full deployment lifecycle of a Node.js web application using **GitHub Actions**, with the app granted secure access to **Azure Blob Storage** via Managed Identity to display blob data on the frontend.

**What I did:**
- Built a CI/CD pipeline using GitHub Actions to auto-deploy on every code push
- Assigned **Storage Blob Data Reader** role to the App Service via Managed Identity
- App dynamically reads and displays Azure Blob Storage data without any stored credentials
- Demonstrated the principle of least privilege in a real deployment

**Skills demonstrated:** GitHub Actions, CI/CD, Azure App Service, Managed Identity, RBAC, Blob Storage

---

### 🌐 5. Azure Static Website on Blob Storage
**Cloud:** Azure | **Focus:** Storage, Static Hosting

Hosted a static website using **Azure Blob Storage** static website hosting feature, demonstrating cost-effective, serverless web hosting without any VM or App Service required.

**Skills demonstrated:** Azure Blob Storage, Static Website Hosting, Azure CDN concepts

---

### 🖥️ 6. Windows VM with IIS Web Server
**Cloud:** Azure | **Focus:** Virtual Machines, Web Server Configuration

Provisioned a Windows Virtual Machine on Azure and configured **IIS (Internet Information Services)** as a web server, including NSG rules to allow HTTP/HTTPS traffic.

**Skills demonstrated:** Azure Virtual Machines, IIS, Network Security Groups, Windows Server

---

### 🔄 7. App Service Deployment via GitHub Integration
**Cloud:** Azure | **Focus:** CI/CD, App Service

Configured continuous deployment of a web application to **Azure App Service** directly from a GitHub repository, enabling automatic redeployment on every push to the main branch.

**Skills demonstrated:** Azure App Service, GitHub Integration, Continuous Deployment

---

### 🛡️ 8. Entra ID & Network Security Configuration
**Cloud:** Azure | **Focus:** Identity, Network Security

Explored **Microsoft Entra ID** role assignments and configured **Network Security Groups (NSGs)** with custom inbound and outbound rules to enforce least-privilege network access.

**Skills demonstrated:** Microsoft Entra ID, RBAC, NSG, Inbound/Outbound Rules, Network Hardening

---

## 🧰 Tech Stack

| Category | Tools & Technologies |
|---|---|
| Cloud Platforms | AWS, Microsoft Azure |
| Compute | EC2, Azure VM, App Service |
| Security & IAM | Azure Key Vault, Managed Identity, Entra ID, RBAC, NSG |
| Networking | Load Balancers, VPC, NSG, Inbound/Outbound Rules, Nginx |
| Automation & DevOps | GitHub Actions, Bash Scripting, Cron Jobs, Python |
| Storage | Azure Blob Storage, AWS S3 |
| Monitoring | Custom Python monitoring, Email Alerts, SSL Tracking |
| OS | Linux (Ubuntu), Windows Server |

---

## 📜 Certifications & Learning Path

| Certification | Status |
|---|---|
| AZ-104: Microsoft Azure Administrator | Practice Assessment Passed ✅ |
| AWS Solutions Architect Associate (SAA) | In Progress 🔄 |
| ISC2 Certified in Cybersecurity (CC) | Exam Scheduled April 2026 📅 |

---

## 📬 Connect with Me

- 💼 [LinkedIn](#) ← www.linkedin.com/in/rayyan-mudassar-1a8799375
- 📧 [Email](#) ← rayyanmudassar4@gmail.com

---

*This portfolio is actively maintained and updated as I complete new labs and projects.*
