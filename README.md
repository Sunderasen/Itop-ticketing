
# ITOP Ticketing
ITOP Deployment Guide
This guide outlines the steps to deploy ITOP, an open-source ticketing tool, on AWS infrastructure using two Linux instances for the application and database.

# Prerequisites
•	AWS Free Tier Account
•	Two Linux Instances (App & DB) – RHEL Based or Ubuntu
•	Registered Domain Name
•	SSL Certificate
•	For detailed information on ITOP, refer to the official ITOP Installation Guide.


# Steps to be Performed
1. Create Two Security Groups in AWS
Create security groups for both the App and DB servers with appropriate inbound and outbound rules.

2. Create Two Instances – App & DB
App Server: Host the ITOP application.
DB Server: Host the MySQL database.
3. Configure App Server
Follow the instructions below to install and configure Apache, PHP, and the ITOP tool on the App server.

4. Configure DB Server
Set up MySQL for the ITOP application and create the necessary database and users.

5. Install ITOP Tool on the App Server
Install ITOP by downloading it from Sourceforge and configuring it with the required packages.

6. Configure SSL on App Server
Install an SSL certificate for secure communication.

7. Configure DNS in DNS Control Panel
Point your domain to the public IP address of the App server and configure DNS records.

![Logo](https://github.com/Sunderasen/html/blob/main/image.png?raw=true)






