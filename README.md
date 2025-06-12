# AWS Zero Trust Lab: A Case Study

## 🎯 Project Goal

To design and deploy a secure AWS environment using Zero Trust principles. This includes strict identity-based access, segmented networking, and centralized logging for auditing.

## 🔐 Key Principles

- No implicit trust between services
- All actions require authenticated identity
- All activity is logged and monitored

## ⚙️ Tech Stack

- AWS EC2, IAM, VPC, CloudTrail, CloudWatch
- AWS CloudFormation (IaC)
- GitHub Codespaces (iPad-based dev environment)
- CLI tools (AWS CLI, jq)

## 📐 Architecture Plan

- Public + private subnets
- Bastion host for controlled SSH access
- IAM roles with least privilege
- CloudTrail → S3 for log retention

## 🚧 Status

| Feature                       | Status  |
|------------------------------|---------|
| VPC Setup                    | ⏳       |
| IAM Role Creation            | ⏳       |
| Bastion Host Config          | ⏳       |
| CloudTrail Logging           | ⏳       |
| Access Restrictions Enforced | ⏳       |

## 🧠 Notes & Reflections

See: `notes/reflections.md`
