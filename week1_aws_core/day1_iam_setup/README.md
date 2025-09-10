# Week 1 - Day 1: IAM Setup

## 📚 Concepts Covered
- AWS global infrastructure (Regions, AZs, Edge)
- IAM basics (users, groups, roles, policies)
- Root account security (MFA, least privilege)

## 💻 Hands-On Tasks
- [x] Secured root account with MFA
- [x] Created `admin-user` with `AdministratorAccess`
- [x] Configured AWS CLI with `aws configure`
- [x] Created IAM role for EC2 → S3 read access

## 📝 Commands Used
```bash
aws configure
aws s3 ls
