# 🌍 AWS EC2 Cross-Region AMI Migration & Disaster Recovery

<p align="center">

![AWS](https://img.shields.io/badge/AWS-EC2-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows-Server-0078D4?style=for-the-badge&logo=windows)
![IIS](https://img.shields.io/badge/Microsoft-IIS-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</p>

## 📌 Project Overview

This project demonstrates a real-world **AWS Disaster Recovery** solution using **Amazon EC2**, **Amazon Machine Images (AMI)**, and **Microsoft IIS**.

A Windows Server EC2 instance hosting an IIS website was deployed in the **Mumbai Region**, converted into a custom AMI, copied to the **Singapore Region**, and launched as a new EC2 instance to successfully restore the website.

---

# 🏗 Architecture Diagram

<p align="center">
<img src="Architecture-diagram.png" width="100%">
</p>

---

# ☁ AWS Services Used

- Amazon EC2
- Amazon Machine Image (AMI)
- Amazon EBS
- Microsoft IIS
- Security Groups
- Remote Desktop (RDP)

---

# 🚀 Project Workflow

```text
Windows Server EC2
        │
        ▼
 Host Website using IIS
        │
        ▼
 Create Custom AMI
        │
        ▼
 Copy AMI to Singapore Region
        │
        ▼
 Launch New EC2 Instance
        │
        ▼
 Connect using RDP
        │
        ▼
 Verify Website
        │
        ▼
 Disaster Recovery Completed
```

---

# 📸 Project Screenshots

## 🖥 Original Windows Server

<p align="center">
<img src="screenshot/original-instance.png" width="90%">
</p>

---

## 💾 Create Custom AMI

<p align="center">
<img src="screenshot/amicopy-successful.png" width="90%">
</p>

---

## 🌏 Copied AMI in Singapore

<p align="center">
<img src="screenshot/destination-ami.png" width="90%">
</p>

---

## 🚀 Launch New EC2 Instance

<p align="center">
<img src="screenshot/lauchinstance.png" width="90%">
</p>

---

## ⚙ Configure EC2 Instance

<p align="center">
<img src="screenshot/instancecreate.png" width="90%">
</p>

---

## 🔑 Retrieve Windows Password

<p align="center">
<img src="screenshot/password.png" width="90%">
</p>

---

## 🖥 Remote Desktop Connection

<p align="center">
<img src="screenshot/remote-desktopconnection.png" width="90%">
</p>

---

## 🌐 Verify Website on Localhost

<p align="center">
<img src="screenshot/search-localhost.png" width="90%">
</p>

---

## ✅ Deployment Successful

<p align="center">
<img src="screenshot/success_msg.png" width="90%">
</p>

---

## 🎉 Website Running Successfully

<p align="center">
<img src="screenshot/website-running.png" width="90%">
</p>

---

# ✨ Key Features

- Windows Server EC2 Deployment
- IIS Website Hosting
- Custom AMI Creation
- Cross-Region AMI Migration
- Disaster Recovery Implementation
- Website Restoration
- Secure RDP Access

---

# 📚 Skills Demonstrated

- AWS EC2
- Windows Server
- Microsoft IIS
- Amazon Machine Images (AMI)
- Disaster Recovery
- Cross-Region Migration
- AWS Security Groups
- Git & GitHub

---

# 👨‍💻 Author

**Ajwa Farooq**

BS Software Engineering Student

🌐 **GitHub:** https://github.com/Ajwafarooq

---

# ⭐ Support

If you found this project useful, please consider giving this repository a **Star ⭐**.