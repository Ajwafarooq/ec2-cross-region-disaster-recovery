# 🌍 AWS EC2 Cross-Region AMI Migration & Disaster Recovery (Windows Server IIS)

<p align="center">

![AWS](https://img.shields.io/badge/AWS-EC2-orange?style=for-the-badge&logo=amazonaws)
![Windows Server](https://img.shields.io/badge/Windows-Server-blue?style=for-the-badge&logo=windows)
![IIS](https://img.shields.io/badge/Microsoft-IIS-green?style=for-the-badge)
![Disaster Recovery](https://img.shields.io/badge/Disaster-Recovery-red?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)

</p>

---

# 📑 Table of Contents

- Project Overview
- Architecture Diagram
- Project Objectives
- AWS Services Used
- Technologies Used
- Solution Workflow
- Project Structure
- Project Screenshots
- Key Features
- Learning Outcomes
- Future Improvements
- Author
- License

---

# 📌 Project Overview

This project demonstrates a real-world **AWS Disaster Recovery (DR)** solution using **Amazon EC2** and **Amazon Machine Images (AMI)**.

A Windows Server EC2 instance hosting the **CloudSphere Solutions** website with **Microsoft IIS** was deployed in the **Mumbai Region (ap-south-1)**. A custom AMI was created from the running instance, copied to the **Singapore Region (ap-southeast-1)**, and used to launch a new Windows Server EC2 instance.

The migrated server successfully restored the website, demonstrating a practical **Cross-Region Disaster Recovery** strategy on AWS.

---

# 🏗 Architecture Diagram

<p align="center">

![Architecture Diagram](diagrams/Architecture-diagram.png)

</p>

---

# 🎯 Project Objectives

- Deploy a Windows Server EC2 instance
- Host a website using Microsoft IIS
- Create a custom Amazon Machine Image (AMI)
- Copy the AMI to another AWS Region
- Launch a new EC2 instance from the copied AMI
- Verify website functionality after migration
- Demonstrate AWS Disaster Recovery implementation

---

# ☁ AWS Services Used

| AWS Service | Purpose |
|-------------|---------|
| Amazon EC2 | Virtual Windows Server |
| Amazon Machine Image (AMI) | Server Backup |
| Cross-Region AMI Copy | Disaster Recovery |
| Amazon EBS | Storage Volume |
| Security Groups | Firewall Rules |
| Microsoft IIS | Website Hosting |
| Remote Desktop (RDP) | Remote Access |

---

# 💻 Technologies Used

- Amazon Web Services (AWS)
- Windows Server
- Microsoft IIS
- Amazon EC2
- Amazon Machine Images (AMI)
- Remote Desktop Protocol (RDP)
- Git
- GitHub

---

# 🔄 Solution Workflow

```text
                      User
                        │
                        ▼
      AWS Mumbai Region (Primary)
      Windows Server EC2 + IIS
                        │
                 Host Website
                        │
                Create Custom AMI
                        │
              Cross-Region AMI Copy
                        │
                        ▼
   AWS Singapore Region (Disaster Recovery)
                        │
             Launch New EC2 Instance
                        │
              Connect using RDP
                        │
              Verify Website Access
                        │
                        ▼
        Disaster Recovery Successful ✅
```

---

# 📂 Project Structure

```text
aws-ec2-cross-region-ami-migration/
│
├── README.md
├── LICENSE
│
├── diagrams/
│   └── Architecture-diagram.png
│
└── screenshots/
    ├── 01-original-instance.png
    ├── 02-create-ami.png
    ├── 03-ami-copy-successful.png
    ├── 04-destination-ami.png
    ├── 05-launch-instance.png
    ├── 06-new-instance-running.png
    ├── 07-password.png
    ├── 08-rdp-connection.png
    ├── 09-localhost-test.png
    ├── 10-success-message.png
    └── 11-website-running.png
```

---

# 📷 Project Screenshots

## 1️⃣ Original Windows Server

![Original Instance](screenshots/01-original-instance.png)

---

## 2️⃣ Create AMI

![Create AMI](screenshots/02-create-ami.png)

---

## 3️⃣ AMI Copy Successful

![AMI Copy](screenshots/03-ami-copy-successful.png)

---

## 4️⃣ Destination AMI (Singapore Region)

![Destination AMI](screenshots/04-destination-ami.png)

---

## 5️⃣ Launch New EC2 Instance

![Launch Instance](screenshots/05-launch-instance.png)

---

## 6️⃣ New EC2 Instance Running

![Running Instance](screenshots/06-new-instance-running.png)

---

## 7️⃣ Retrieve Administrator Password

![Password](screenshots/07-password.png)

---

## 8️⃣ Remote Desktop Connection

![RDP](screenshots/08-rdp-connection.png)

---

## 9️⃣ Localhost Website Verification

![Localhost](screenshots/09-localhost-test.png)

---

## 🔟 Successful Deployment

![Success](screenshots/10-success-message.png)

---

## 1️⃣1️⃣ Website Running on Disaster Recovery Server

![Website Running](screenshots/11-website-running.png)

---

# ✨ Key Features

- Windows Server Deployment
- IIS Website Hosting
- Custom AMI Creation
- Cross-Region AMI Migration
- Disaster Recovery Implementation
- EC2 Restoration
- Secure RDP Access
- Website Verification
- Cloud Backup Strategy

---

# 📚 Learning Outcomes

Through this project, I learned how to:

- Deploy Windows Server on Amazon EC2
- Configure Microsoft IIS
- Create and manage Amazon Machine Images (AMI)
- Perform Cross-Region AMI Migration
- Launch EC2 instances from custom AMIs
- Implement Disaster Recovery strategies
- Secure Windows Server using Security Groups
- Manage cloud infrastructure using AWS

---

# 🚀 Future Improvements

- Route 53 DNS Failover
- Elastic Load Balancer (ELB)
- Auto Scaling Group
- AWS Backup Integration
- CloudWatch Monitoring
- SSL Certificate (HTTPS)
- Custom Domain Name
- Infrastructure as Code using Terraform

---

# 👨‍💻 Repository

```
aws-ec2-cross-region-ami-migration
```

---

# 👩‍💻 Author

**Ajwa Farooq**

BS Software Engineering Student

National Textile University

**GitHub Profile**

https://github.com/Ajwafarooq

---

# 📄 License

This project is created for **educational and portfolio purposes**.

---

# ⭐ Support

If you found this project useful, please consider giving this repository a **⭐ Star** on GitHub.

Thank you for visiting this project!