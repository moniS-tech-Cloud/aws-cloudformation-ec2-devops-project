# AWS CloudFormation EC2 Deployment

This project demonstrates Infrastructure as Code using AWS CloudFormation.

## Services Used

- AWS CloudFormation
- Amazon EC2
- Security Groups
- Apache Web Server
- Linux

## Architecture

User → Internet → Security Group → EC2 Instance → Apache Web Server

## Deployment Steps

1. Create a CloudFormation template (template.yaml).
2. Deploy the stack using AWS CloudFormation.
3. CloudFormation automatically launches an EC2 instance.
4. Configure the server and install Apache web server.
5. Host web application accessible through the instance public IP.
   
## Files in This Repository

- **template.yaml** – CloudFormation template to create EC2 instance
- **commands.md** – Linux commands used to install Apache
- **architecture.png** – AWS architecture diagram   
   
## Purpose

This project demonstrates how DevOps engineers automate cloud infrastructure using Infrastructure as Code (IaC).
