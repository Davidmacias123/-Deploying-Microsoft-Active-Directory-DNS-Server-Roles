# 🖥️ Deploying Microsoft Active Directory & DNS Server  
### A beginner-friendly, step-by-step project with full screenshots

## 📘 Project Overview

This project demonstrates how to deploy **Active Directory Domain Services (AD DS)** and the **DNS Server** role on Windows Server. Each step is explained simply so anyone following the guide understands what is happening and why.

Active Directory manages users, computers, groups, and security settings.  
DNS helps devices find each other by name.

This project includes screenshots for every part of the deployment so learners can follow the process visually from beginning to end.

All screenshots are stored inside the `/screenshots` directory, grouped by each major step.

---

# 📂 Screenshot Structure

```
/screenshots
    /1_server_setup
    /2_ad_ds_dns_installation
    /3_dc_promotion
    /4_dns_configuration
    /5_validation
    /6_ou_user_group_creation
```

Each section below shows exactly which screenshot belongs to each folder.

---

# 🧩 1. Preparing the Server

These steps prepare the server so it can function as a reliable domain controller.

---

## 🔹 1.1 Configure a Static IP Address

A static IP gives the server a permanent network address so clients can always find it.

**Upload to:** `/screenshots/1_server_setup`  
**Screenshots:**  
- `static ip address.png`  
- `hostname, ip static not dhcp.png`

---

## 🔹 1.2 Verify Server Manager & System Info

**Upload to:** `/screenshots/1_server_setup`  
**Screenshot:**  
- `server manager was already installed and look like this.png`

---

## 🔹 1.3 Test Network Connectivity

These tests confirm that the network settings are correct.

**Upload to:** `/screenshots/1_server_setup`  
**Screenshots:**  
- `verifying connectivity part 1.png`  
- `verifying connectivity part 2.png`

---

## 🔹 1.4 Update Windows Server

**Upload to:** `/screenshots/1_server_setup`  
**Screenshot:**  
- `Screenshot 2025-11-07 211408.png`

---

# 🧩 2. Installing AD DS & DNS Roles

These roles allow the server to manage a domain and resolve network names.

**Upload to:** `/screenshots/2_ad_ds_dns_installation`  
**Screenshots:**  
- `open server manager on windows server.png`  
- `role basefeature base isntallation.png`  
- `destination server.png`  
- `server roles.png`  
- `confirmation.png`

---

# 🧩 3. Promoting the Server to a Domain Controller

This process activates Active Directory and creates the domain.

**Upload to:** `/screenshots/3_dc_promotion`  
**Screenshots:**  
- `promote server to domain controller.png`  
- `forest name.png`  
- `domain controller options.png`  
- `prerequisites check.png`  
- `review options.png`

---

# 🧩 4. Configuring DNS

DNS is required for Active Directory to function. These screenshots confirm proper DNS installation and configuration.

**Upload to:** `/screenshots/4_dns_configuration`  
**Screenshots:**  
- `verify ad ds dns installation.png`  
- `confirm forward and reverse lookup zones are functioning.png`

---

# 🧩 5. Validating the Deployment

This step confirms that the new domain is working correctly.

**Upload to:** `/screenshots/5_validation`  
**Screenshots:**  
- `active directory users and computers and dns.png`  
- `test dns resolution.png`  
- `event logs.png`  
- `event logs better.png`

---

# 🧩 6. Creating Organizational Units, Users, and Groups

Creating users and groups prepares the domain for real-world management.

**Upload to:** `/screenshots/6_ou_user_group_creation`  
**Screenshots:**  
- `organizational units.png`  
- `created a user inside david_admins organizational unit.png`  
- `put password A@123456789.png`  
- `added password A@1234.png`  
- `created group.png`  
- `proof to show the user and the group was created and on the bottom left you can see the organizational unit called david_admins.png`

---

# 🎉 Final Result

This project successfully deploys a complete domain environment with:

✔ Active Directory Domain Services  
✔ DNS Server  
✔ Static IP configuration  
✔ Domain controller promotion  
✔ A functional domain: **david.local**  
✔ DNS forward & reverse lookup  
✔ Organizational Units  
✔ User accounts  
✔ Security groups  
✔ Validation through ADUC, DNS Manager, and event logs  

Everything is configured, tested, and demonstrates a real-world Active Directory deployment.

---

# 📄 Suggested Project Description (for GitHub)

**A complete beginner-friendly guide showing how to deploy Active Directory and DNS on Windows Server. Includes static IP configuration, AD DS installation, domain controller promotion, DNS verification, and the creation of OUs, users, and groups — all fully documented with screenshots.**
