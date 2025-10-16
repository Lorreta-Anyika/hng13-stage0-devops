# HNG13 DevOps Stage 0 Project

## 👤 Name
Anyika, Uchechukwu Lorreta

## Slack Username
@lorretaU

## Project Overview
This project was completed as part of the **HNG13 Stage 0 DevOps Challenge**.  
The task required deploying a live NGINX web server that hosts a custom HTML page accessible from the public internet.  
It simulates a real-world DevOps workflow — managing a GitHub repository, configuring a web server, and documenting a deployment process.

---

## Steps I Took

### 1️⃣ GitHub Setup
- Forked the official `hng13-stage0-devops` repository.  
- Added a `README.md` file containing project and personal details.  
- Documented my deployment process clearly for verification.

### 2️⃣ Cloud Server Deployment
- Set up a **free-tier AWS EC2 instance** running Ubuntu.  
- Configured SSH access using an RSA key pair for secure login.  
- Updated and upgraded the server using `sudo apt update && sudo apt upgrade`.  

### 3️⃣ Web Server Configuration
- Installed and started **NGINX** to handle HTTP web requests.  
- Verified the default server page to confirm successful setup.  
- Edited the file `/var/www/html/index.nginx-debian.html` to include:
  - My name and Slack username  
  - Platform name (AWS EC2)
  - Deployment date  
- Reloaded NGINX and tested accessibility on port 80.

### 4️⃣ Verification
- Accessed the webpage publicly using:  
  👉 **http://13.60.92.199//**  
- Confirmed server uptime, accessibility, and correct content display.

---

## Skills Gained / Improved
- **Cloud Infrastructure Management (AWS EC2)**  
- **Linux Command Line Operations**  
- **NGINX Installation & Configuration**  
- **Secure Shell (SSH) Authentication**  
- **Basic Web Server Deployment**  
- **Version Control with Git & GitHub**  
- **Technical Documentation**

---

## Server IP / Domain
http://13.60.92.199/

## Deployment Platform
AWS EC2 (Ubuntu)

## Date Deployed
October 17, 2025

---

## 🏁 Reflection
This task helped me understand the practical side of DevOps — how code, servers, and automation connect to deliver real web experiences.  
It built my confidence in working with Linux, networking, and deployment workflows while sharpening my problem-solving mindset.

---
