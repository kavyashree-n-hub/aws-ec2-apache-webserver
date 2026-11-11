# aws-ec2-apache-webserver
My first AWS project - Launching an EC2 instance and hosting a web page using Apache.

AWS EC2 Apache Web Server Project
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
Launch EC2 Instance
Created an Amazon EC2 instance
Configured Security Groups
Enabled SSH and HTTP access
Connect to EC2
ssh -i key.pem ec2-user@public-ip
Update Server
sudo yum update -y
Install Apache
sudo yum install httpd -y
Start Apache
sudo systemctl start httpd
sudo systemctl enable httpd
Create Web Page
cd /var/www/html
sudo vi index.html

Screenshots
EC2 Instance Running 
ec2-instance.png

Terminal Output
terminal-output.png

Hosted Webpage
webpage-output.png

Learning Outcomes
AWS EC2 Basics
Security Groups
SSH Connectivity
Linux Administration
Apache Web Server Setup
Website Hosting on Cloud
Author
Kavyashree N
