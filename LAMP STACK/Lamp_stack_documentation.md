WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS

Introduction:

A “LAMP” stack is a group of open source software that is typically installed together in order to enable a server to host dynamic websites and web apps written in PHP. This term is an acronym which represents the Linux operating system with the Apache web server. The site data is stored in a MySQL database, and dynamic content is processed by PHP. In order to complete this project, we need an AWS account and a server with Ubuntu OS Server.

STEP ONE: Create and EC2 instance on AWS. Using the AWS Management Console, we can set up an ubuntu server in our most preferred region and connect to the EC2 instance using SSH cryptographic key known as PEM(Privacy Enhanced Mail) file.

1_![Ec2 Creation](./Images/Ec2_Creation.PNG)
2_The security group was configured with the following inbound rules:

- Allow traffic on port 80 (HTTP) with source from anywhere on the internet.
- Allow traffic on port 443 (HTTPS) with source from anywhere on the internet.
- Allow traffic on port 22 (SSH) with source from any IP address. This is opened by default.
2.
- ![Security_Rule](./Images/2nd_Stage.PNG)

