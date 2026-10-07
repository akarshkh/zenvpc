# ZenVPC — Secure AWS Infrastructure

ZenVPC is a multi-tier AWS infrastructure project designed to demonstrate secure cloud networking, compute, database deployment, and access control using Amazon Web Services.

The architecture uses public and private subnets to separate application components and database resources while controlling traffic through route tables, an Internet Gateway, security groups, and IAM.

---

## 🏗️ Architecture

The project includes:

- Amazon VPC
- Public and private subnets
- Route tables
- Internet Gateway
- Security Groups
- IAM
- Amazon EC2
- Amazon RDS
- Amazon S3
- AWS Amplify

## Architecture Overview

```text
                    Internet
                       │
                       ▼
              ┌─────────────────┐
              │   AWS Amplify   │
              │    Frontend     │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │   Amazon VPC    │
              │                 │
              │  Public Subnet  │
              │  ┌───────────┐  │
              │  │    EC2     │  │
              │  └─────┬─────┘  │
              │        │        │
              │  Private Subnet │
              │  ┌───────────┐  │
              │  │    RDS    │  │
              │  └───────────┘  │
              └─────────────────┘
```

---


## 🎥 Project Demo

https://github.com/user-attachments/assets/db38cb82-6962-43dd-a2ba-4b16491b72f9

---

## ☁️ AWS Services

| Service | Purpose |
|---|---|
| Amazon VPC | Network isolation and infrastructure organization |
| Subnets | Separation of public and private resources |
| Route Tables | Traffic routing within the VPC |
| Internet Gateway | Internet connectivity for public resources |
| Security Groups | Network-level access control |
| IAM | Identity and access management |
| Amazon EC2 | Backend/application hosting |
| Amazon RDS | Relational database hosting |
| Amazon S3 | Cloud storage |
| AWS Amplify | Frontend deployment |

---

## 🔐 Security & Networking

The infrastructure uses:

- Public and private subnet architecture
- VPC-based network isolation
- Route tables for controlled traffic flow
- Security groups for instance-level access control
- IAM for identity and access management
- Private subnet placement for database resources

---

## 🚀 Deployment

### Prerequisites

- AWS account
- AWS Management Console access
- Basic understanding of VPC networking
- EC2, RDS, IAM, and Amplify access

### Core Deployment Steps

1. Create an Amazon VPC.
2. Configure public and private subnets.
3. Configure route tables.
4. Attach an Internet Gateway to the VPC.
5. Configure security groups.
6. Configure IAM permissions and roles.
7. Deploy the backend application on Amazon EC2.
8. Deploy Amazon RDS within the private subnet.
9. Deploy the frontend using AWS Amplify.

---

## 🛠️ Technologies

- AWS VPC
- Amazon EC2
- Amazon RDS
- Amazon S3
- AWS Amplify
- IAM
- Route Tables
- Internet Gateway
- Security Groups
- Public & Private Subnets

---

## 🎯 Project Objective

The project demonstrates practical understanding of AWS infrastructure design, cloud networking, resource isolation, access control, and multi-tier application architecture.

---

## 📌 Project Status

Completed cloud infrastructure project.
