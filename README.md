# AWS EC2 Launch Task – Manual + Terraform

## 📌 Overview
This task will show two easy ways to launch an AWS EC2 instance:
1. **Manually** using the AWS Management Console  
2. **Automatically** using **Terraform (Infrastructure as Code)**

The purpose of this task is to learn about both methods and see how cloud setup becomes simpler and more repeatable with automation.

---  

## 🛠 Prerequisites
- AWS account
- Basic knowledge of EC2
- Terraform installed
- AWS CLI configured

---

## 🚀 Method 1: Manual EC2 Launch
- Log in to AWS Console
- Go to **EC2 → Launch Instance**
- Select AMI, instance type, key pair, and security group
- Launch the instance

✅ Good for learning  
❌ Not scalable or repeatable

---

## ⚙️ Method 2: EC2 Launch Using Terraform
- Create Terraform configuration files
- Initialize Terraform
- Apply the configuration to launch EC2 automatically

✅ Fast, repeatable, and scalable  
✅ Best practice for real-world projects

---

## 🧹 Cleanup
To avoid extra charges:
- Terminate the EC2 instance (manual)
- Or run `terraform destroy` (Terraform)

---

## 📝 Conclusion
This task demonstrates the difference between **manual cloud setup** and **Infrastructure as Code**. Terraform simplifies infrastructure management, making it cleaner and more professional.

---

✨ *Simple, efficient, and cloud-ready.*
