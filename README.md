#  Terraform AWS Infrastructure: Scalable Web App with ALB & S3

This repository contains a Terraform-based automation project for deploying a highly available and scalable web application on AWS.  
The infrastructure is designed with **best practices in networking, security, and load balancing** to ensure reliability and fault tolerance.

---

##  Key Features
--->  **Custom VPC** with two public subnets across multiple Availability Zones  
--->  **Internet Gateway & Route Tables** for external connectivity  
--->  **Security Groups** allowing inbound SSH (22) & HTTP (80) traffic  
--->  **Two EC2 Web Servers** automatically bootstrapped with user data scripts  
--->  **Application Load Balancer (ALB)** to distribute traffic between servers  
--->  **S3 Bucket** for static storage or future extension  
--->  **Health Checks & Target Groups** to ensure application availability  
--->  **Terraform Output** to retrieve the ALB DNS for quick access  

---

##  Architecture Diagram
![AWS Terraform Infra](https://github.com/user-attachments/assets/84303211-e973-438a-a04a-ae0b9776e37a)


##  Prerequisites
Before deploying, make sure you have:  
- ✅ [Terraform](https://developer.hashicorp.com/terraform/downloads) installed  
- ✅ [AWS CLI](https://docs.aws.amazon.com/cli/) configured with credentials  
- ✅ An AWS account with sufficient IAM permissions  


## AWS Services Used ##

-->Amazon VPC, Subnets, Internet Gateway, Route Tables
-->Amazon EC2 (Web Servers with User Data)
-->Application Load Balancer (ALB)
-->Target Groups & Listener Rules
-->Amazon S3 Bucket
-->Security Groups

Author

Built with ❤️ and ☕ by SoniaAkhtar
