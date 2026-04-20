# Day 2 – AWS Setup & CLI Configuration

## 📌 Objective
Set up secure access to AWS and configure the local development environment for serverless deployment.

---

## ☁️ Platform
Amazon Web Services (AWS)

---

## 🔐 IAM Configuration
- Created IAM user for development purposes
- Generated new access keys after credential reset
- Avoided using root account for security best practices

---

## 💻 AWS CLI Setup

Configured AWS CLI using:

```bash
aws configure
```
## Configuration:
Region: us-east-1
Output format: json

## ⚠️ Issues Encountered
1. Incorrect IAM Command
-Incorrect:
aws iam list users
-Correct:
aws iam list-users

2. Output Format Error
-Incorrect:
Json
-Correct:
json
🔐 Security Lesson

Access keys were accidentally exposed during setup and were immediately rotated.

## Lesson learned:
-Never expose AWS credentials publicly
-Always rotate compromised keys immediately

## 🧠 Key Learnings
-Importance of IAM in cloud security
-CLI syntax sensitivity
-Secure credential management
-AWS authentication flow using CLI

## 🚀 Outcome
-AWS CLI successfully configured
-IAM user validated
-Environment ready for Lambda development
