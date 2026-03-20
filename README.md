**OWASP Juice Shop Security Assessment**

**Overview**

This repository contains a security assessment of the OWASP Juice Shop application conducted in a Kali Linux environment using Docker. The assessment was performed as part of an internship evaluation.

The objective was to identify, exploit, and document common web application vulnerabilities using practical penetration testing techniques.


**Environment Setup**

* Operating System: Kali Linux (Virtual Machine)
* Deployment Method: Docker
* Target Application: OWASP Juice Shop
* URL:http://localhost:3000


**Tools Used**

* Kali Linux
* Docker
* Burp Suite Community Edition
* Web Browser (Chromium)


**Vulnerabilities Identified**

1\. SQL Injection (Authentication Bypass)

2\. Cross-Site Scripting (XSS)

3\. Insecure Direct Object Reference (IDOR)

4\. Weak Authentication Mechanism

5\. Security Misconfiguration

6\. Sensitive Data Exposure (JWT)

7\. Broken Access Control \& Information Disclosure


**How to Run OWASP Juice Shop using Docker**

**Step 1: Install Docker (if not installed)**

    sudo apt update
    sudo apt install docker.io

**Step 2: Start Docker Service**

    sudo systemctl start docker

**Step 3: Pull Juice Shop Image**

    sudo docker pull bkimminich/juice-shop

**Step 4: Run the Container**

    sudo docker run -d -p 3000:3000 bkimminich/juice-shop

**Step 5: Access the Application**

    Open your browser and go to:
    http://localhost:3000


**Proof of Work**

Screenshots demonstrating each identified vulnerability are available in the `screenshots/` directory.


**Repository Structure**

* report.pdf - Full security assessment report
* screenshots/ - Evidence of vulnerabilities
* README.md - Project documentation





