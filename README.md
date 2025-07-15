# VPC with Public and Private Subnets

This project sets up a custom VPC with:
- 2 public subnets
- 2 private subnets
- NAT Gateway for private subnet internet access
- Security Groups and NACLs

## ✅ AWS Services Used
- Amazon VPC
- Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- NACLs

## 🚀 Setup Instructions
1. Use the AWS VPC Wizard or CLI to create a new VPC
2. Add public and private subnets across 2 AZs
3. Attach IGW and set routing for public subnet
4. Add NAT Gateway for private subnet internet access
5. Create appropriate security groups and NACLs

## 💡 Bonus
- Add a Bastion Host in the public subnet for SSH access to private instances

## 📘 Visual Diagram
(Include a VPC architecture diagram here)
