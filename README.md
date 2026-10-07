# ZenVPC — Secure AWS Infrastructure

ZenVPC is a multi-tier AWS infrastructure project designed to demonstrate secure cloud networking, compute, database deployment, and access control using Amazon Web Services.

The architecture uses public and private subnets to separate application components and database resources while controlling traffic through route tables, an Internet Gateway, security groups, and IAM.

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

### Architecture Overview

```text
                    Internet
                       │
                       ▼
              ┌─────────────────┐
              │  AWS Amplify    │
              │   Frontend      │
              └────────┬────────┘
                       │
                       ▼
              ┌─────────────────┐
              │   Amazon VPC    │
              │                 │
              │  Public Subnet  │
              │  ┌───────────┐  │
              │  │   EC2     │  │
              │  └─────┬─────┘  │
              │        │        │
              │  Private Subnet │
              │  ┌───────────┐  │
              │  │    RDS    │  │
              │  └───────────┘  │
              └─────────────────┘
