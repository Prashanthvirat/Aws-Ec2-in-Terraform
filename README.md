# AWS EC2 Infrastructure using Terraform

This project demonstrates how to provision an **Amazon EC2 instance** on **AWS** using **Terraform (Infrastructure as Code)**.  
It is designed for beginners and showcases best practices such as provider configuration, variable usage, and proper Git hygiene.

---

## 📌 Project Overview

Using Terraform, this project:
- Creates an EC2 instance on AWS
- Uses a reusable and modular Terraform structure
- Follows best practices by excluding sensitive and generated files from Git

---

## 🛠️ Technologies Used

- **Terraform**
- **AWS EC2**
- **AWS IAM**
- **Git & GitHub**
- **AWS CLI**

---

## 📂 Project Structure

Aws-Ec2-in-Terraform/
│
├── main.tf # EC2 resource definition
├── provider.tf # AWS provider configuration
├── variables.tf # Input variables
├── outputs.tf # Output values
├── .gitignore # Ignored files (.terraform, tfstate)
└── README.md # Project documentation
