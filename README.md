# Project 3: Node.js Application Deployment on AWS EC2

## Overview

This project demonstrates how to deploy a Node.js web application on an Amazon EC2 instance.

The application is hosted on a Linux-based virtual server and is accessible through a public IP address. It showcases practical cloud engineering skills including server setup, application deployment, and network configuration.

---

## What I Built

I built and deployed a Node.js web application on AWS EC2.

This involved:

* Launching and configuring an EC2 instance
* Installing Node.js on Amazon Linux
* Creating a custom Node.js server
* Configuring security groups to allow external access (port 3000)
* Running the application and making it publicly accessible

---

## Technologies Used

* AWS EC2
* Node.js
* Amazon Linux
* Security Groups
* Linux Command Line
* HTTP Server (Node.js)

---

## Architecture

A single EC2 instance hosts the Node.js application.

The instance is configured with inbound rules to allow:

* SSH (port 22) for server access
* HTTP (port 80) for web traffic (Project 2)
* Custom TCP (port 3000) for the Node.js application

---

## Deployment Steps

1. Launched an EC2 instance (Free Tier)
2. Connected using EC2 Instance Connect
3. Installed Node.js using package manager
4. Created a Node.js application (`app.js`)
5. Configured security group to allow port 3000
6. Started the application using Node
7. Accessed the app via public IP

---

## Live Demo

http://3.8.159.2:3000

---

## Screenshots

(<img width="1145" height="835" alt="image" src="https://github.com/user-attachments/assets/cf2f572e-e18c-4a90-b9e2-ba4f7ad663dd" />
)

1. Live portfolio landing page
2. EC2 instance running
3. Security group inbound rules
4. Terminal showing app running
5. Node and npm versions
6. Application code

---

## Key Learning Outcomes

* Deploying applications on cloud infrastructure
* Understanding EC2 and virtual servers
* Managing Linux-based environments
* Configuring network access using security groups
* Running and testing a live Node.js application

---

## Future Improvements

* Use PM2 to manage the application process
* Configure Nginx as a reverse proxy
* Attach a domain name
* Add HTTPS (SSL certificate)
* Deploy using CI/CD pipeline

---

## Author

Kingsley Evans
