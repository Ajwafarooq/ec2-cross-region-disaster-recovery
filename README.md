
# 🌍 AWS EC2 Cross-Region AMI Migration & Disaster Recovery (Windows Server IIS)

![AWS](https://img.shields.io/badge/AWS-EC2-orange) ![Windows
Server](https://img.shields.io/badge/Windows-Server-blue)
![IIS](https://img.shields.io/badge/IIS-Web%20Hosting-green) ![Disaster
Recovery](https://img.shields.io/badge/Disaster-Recovery-red)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black)

## 📌 Project Overview

This project demonstrates a real-world Disaster Recovery (DR) workflow
on AWS by creating a custom Amazon Machine Image (AMI) from a Windows
Server EC2 instance, copying the AMI from the **Mumbai Region
(ap-south-1)** to the **Singapore Region (ap-southeast-1)**, and
launching a new EC2 instance from the copied AMI.

The original IIS-hosted CloudSphere Solutions website was successfully
restored in the destination region, demonstrating cross-region backup
and recovery.

## 🎯 Objectives

-   Deploy a Windows Server EC2 instance
-   Host a website using Microsoft IIS
-   Create a custom Amazon Machine Image (AMI)
-   Copy the AMI to another AWS Region
-   Launch a new EC2 instance from the copied AMI
-   Verify website availability after migration
-   Demonstrate Disaster Recovery using AWS

## 🏗 Solution Architecture

![Architecture Diagram](diagrams/Architecture-diagram.png)

## 🔄 Disaster Recovery Workflow

1.  Deploy a Windows Server EC2 instance in the **Mumbai Region (Primary
    Region)**.
2.  Host the website using **Microsoft IIS**.
3.  Create a custom **Amazon Machine Image (AMI)**.
4.  Copy the AMI to the **Singapore Region**.
5.  Launch a new EC2 Windows Server from the copied AMI.
6.  Connect using **Remote Desktop Protocol (RDP)**.
7.  Verify the website is running successfully.

## ☁ AWS Services Used

-   Amazon EC2
-   Amazon Machine Image (AMI)
-   Amazon EBS
-   Microsoft IIS
-   Windows Server
-   Security Groups
-   Remote Desktop Protocol (RDP)

## 📂 Project Structure

``` text
aws-ec2-cross-region-ami-migration/
├── README.md
├── LICENSE
├── diagrams/
│   └── Architecture-diagram.png
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

## 📷 Screenshots

Add the screenshots from the `screenshots/` folder in the same order.

## 📚 Learning Outcomes

-   AMI creation and management
-   Cross-region migration
-   Disaster recovery concepts
-   Windows Server administration
-   IIS hosting
-   AWS EC2 deployment
-   Git & GitHub documentation

## 🚀 Future Enhancements

-   Route 53 Failover
-   Elastic Load Balancer
-   Auto Scaling
-   AWS Backup
-   CloudWatch Monitoring
-   SSL Certificate
-   Infrastructure as Code (Terraform)

## 👩‍💻 Author

**Ajwa Farooq**

BS Software Engineering Student

GitHub: https://github.com/Ajwafarooq

## 📄 License

This project is for educational and portfolio purposes.

## ⭐ Support

If you found this project helpful, please consider giving this
repository a ⭐.
