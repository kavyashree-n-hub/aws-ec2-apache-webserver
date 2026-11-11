# AWS EC2 Apache Web Server Project

Project Overview
This project demonstrates how to launch an Amazon EC2 instance, connect using SSH, install Apache Web Server, and host a simple HTML website.

Technologies Used
AWS EC2
Amazon Linux
Apache HTTP Server
Linux
SSH
HTML

Project Steps
1. Launch EC2 Instance
Created an Amazon EC2 instance
Configured Security Groups
Enabled SSH and HTTP access
2. Connect to EC2
ssh -i key.pem ec2-user@public-ip
3. Update Server
sudo yum update -y
4. Install Apache
sudo yum install httpd -y
5. Start Apache
sudo systemctl start httpd
sudo systemctl enable httpd
6. Create Web Page
cd /var/www/html
sudo vi index.html
Screenshots
EC2 Instance Running
EC2Instance.png

Terminal Output
Terminal Output

Hosted Webpage
First-webpage.jpg

Learning Outcomes
AWS EC2 Basics
Security Groups
SSH Connectivity
Linux Administration
Apache Web Server Setup
Website Hosting on AWS
Author
Kavyashree N
