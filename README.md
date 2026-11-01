# AWS IAM & EC2 Project

Deployed a basic website on an Amazon EC2 instance and set up IAM for secure access.

## What I did
1. Created an IAM user (student-user) with EC2 read-only access
2. Created an IAM role (ec2-basic-role) with a least-privilege policy
3. Launched an Amazon Linux 2023 t3.micro EC2 instance (ap-southeast-2)
4. Created a security group allowing SSH (22) and HTTP (80)
5. Connected using EC2 Instance Connect
6. Installed Apache (httpd) and deployed an HTML page

## Live website
http://3.26.55.8

## Key learnings
- IAM users, roles, policies and least privilege
- Security groups act as a virtual firewall
- Hosting a website on EC2 with Apache

## Screenshots
See the .png files in this repository.
