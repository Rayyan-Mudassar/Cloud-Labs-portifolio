# Azure VM + IIS Web Server Deployment

**Project:** Deploy a Windows VM in Azure using the Azure Portal, install IIS, and host a simple webpage.  
**Author:** Rayyan Mudassar
**Date:** 2025-12-08

---

## Project Overview
This project shows how I created a Windows Server Virtual Machine using the Azure Portal, opened the necessary ports to access it, connected to it with Remote Desktop (RDP), installed IIS, and hosted a simple webpage. All steps were done through the Azure Portal and inside the Windows VM (RDP).

---

## Resources Created 
- **Resource Group**  
- **Virtual Machine (Windows Server 2019)**  
- **Network Security Group (NSG)** (created by the portal and attached to the VM's NIC)  
- **Public IP Address** (assigned to the VM)

---

## 🧠 What I Learned
- How to create and configure a Windows VM using the Azure Portal.  
- How to allow inbound traffic (RDP and HTTP) via the NSG.  
- How to connect to the VM with RDP.  
- How to install IIS inside the VM and host a basic webpage.  
- How to secure the VM after testing and how to stop (deallocate) it to reduce cost.

---

## Steps I Performed

1. Created a **Resource Group** in the Azure Portal and chose a region.  
2. Created a **Windows Virtual Machine** (Windows Server 2019) from the Virtual Machines → Create blade.  
   - Set the admin username and password.  
   - During VM creation I allowed RDP (3389) so I could connect and allowed HTTP (80) so the site could be tested.  
   - The portal created the public IP and NSG automatically and attached them to the VM.
3. After deployment I opened the **VM Overview** page and copied the **Public IP**.  
4. Connected to the VM using **Remote Desktop (RDP)** from my computer using the admin credentials.  
5. Inside the VM I installed **IIS (Internet Information Services)** and replaced the IIS default homepage with my simple HTML page.  
6. From my browser I tested the webpage using the VM’s public IP to confirm the site was live.  
7. After testing I applied basic security steps (restricting RDP or removing it when not needed) and stopped the VM to avoid extra costs.

---

## Security & Cost Management (what I did / recommend)
- Removed RDP access after finishing testing.  
- Stop / Deallocate the VM when not in use to avoid running charges.  
- If keeping RDP open, restrict its source to a single IP (your home IP) using the NSG rule.  
- To fully remove everything later, delete the Resource Group from the portal.

---

## Screenshots
- **vm-iis-demo** page (shows VM name and Public IP).  
- **NSG-rules** (shows HTTP and RDP allowed during setup).  
- **powershell** showing successful IIS installation in the VM.
- **final-site** showing the wepage working.

---



