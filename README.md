# AWS EC2 Linux Server Setup 🚀

This project demonstrates how I launched and connected to a Linux server on AWS using Amazon EC2.

## 📌 Project Overview

In this hands-on cloud project, I:

* Launched an Ubuntu EC2 instance on AWS
* Configured security groups for SSH access
* Created and downloaded an SSH key pair
* Connected securely using SSH from terminal
* Practiced basic Linux server access

This project helped me understand the fundamentals of:

* AWS EC2
* Linux servers
* SSH authentication
* Cloud networking basics

---

# 🛠 AWS Services Used

* Amazon EC2
* Security Groups
* Key Pairs
* Virtual Private Cloud (VPC)

---

# 💻 Instance Configuration

| Setting        | Value                   |
| -------------- | ----------------------- |
| OS             | Ubuntu Server 22.04 LTS |
| Instance Type  | t2.micro                |
| Storage        | 8 GB                    |
| Access Method  | SSH                     |
| Authentication | RSA Key Pair            |

---

# 🔐 SSH Connection Command

```bash
chmod 400 ubuntu-key.pem

ssh -i "ubuntu-key.pem" ubuntu@<PUBLIC-IP>
```

---

# 📷 Project Screenshots

## EC2 Instance Running

(Add screenshot here)

## SSH Login Successful

(Add screenshot here)

---

# 📚 What I Learned

* How to launch cloud servers on AWS
* Difference between public and private access
* How SSH authentication works
* Basic Linux server management
* Importance of cloud security practices

---

# ⚠ Important Notes

* Security Group configured to allow SSH (Port 22)
* PEM key permissions secured using chmod 400
* Instance terminated after practice to avoid charges

---

# 🚀 Future Improvements

* Install and configure Nginx
* Host a static website
* Configure Docker
* Automate deployment using Terraform
* Setup CI/CD pipeline

---

# 👨‍💻 Author

Cloud & DevOps Engineer Journey 🚀
Learning AWS, Linux, DevOps & Cloud Engineering through practical projects.
