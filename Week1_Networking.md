# Week 1: Networking Challenge - 90 Days of DevOps
--------------------------------------------------

Week 1 of the 90 Days of DevOps - 2025 Edition! It's all about Networking, an essential skill for everyone who is seeking to make career in Devops.  

# Understanding OSI & TCP/IP Models  
The OSI (Open Systems Interconnection) and TCP/IP models give a structured way of understanding how data flows in networks.  
Here's how the layers apply to real-world scenarios:  

OSI Model Layers:
-----------------
**Application Layer:** HTTP (web browsing), SMTP (email communication)

**Presentation Layer:** Data encryption (e.g., SSL/TLS)

**Session Layer:** Session establishment for online gaming or video calls

**Transport Layer:** TCP (ensuring data is delivered), UDP (faster, but less reliable for live streaming)

**Network Layer:** IP (router provides routing data between devices)

**Data Link Layer:** MAC address is used for LAN communication

**Physical Layer:** Ethernet cables, Wi-Fi signals

TCP/IP Model Layers:
--------------------
**Application Layer:** HTTP, FTP, DNS

**Transport Layer:** TCP, UDP

**Internet Layer:** IPv4, IPv6

**Network Access Layer:** Ethernet, Wi-Fi

Protocols and Ports for DevOps

Protocols and their port numbers are crucial for setting up services and resolving network problems.

# Commonly Used Protocols:

**HTTP (Port 80):** It uses to browse web pages

**HTTPS (Port 443):** Secure browsing of the web.

**FTP (Port 21):** File transfer protocol.

**SSH (Port 22):** Secure shell for remote access.

**DNS (Port 53):** Domain name resolution.

Why These Are Relevant to DevOps?
-------

**HTTP/HTTPS:** Monitor and troubleshoot web applications.

**FTP:** Transfer build artifacts or deployment packages.

**SSH:** Access servers securely for configuration and management.

**DNS:** Configure domain names for applications and troubleshoot connectivity issues.

# AWS EC2 and Security Groups

How to Launch and Configure Security Groups Step by Step:
---------------------------------------------------------

**1.Launch an EC2 Instance:**  
Sign in to AWS Management Console.  
Go to EC2 and click "Launch Instance."  
Select a free-tier eligible AMI (such as Amazon Linux 2).  
Select an instance type (such as t2.micro).  
Configure instance details and storage.  

**2.Create Security Groups:**  
Go to the Security Groups section.  
Click "Create Security Group."  
Add inbound rules (for example, allow SSH on port 22, HTTP on port 80).  
Assign the Security Group to your EC2 instance.  

**3.Connect to Your Instance:**  
Use an SSH client to connect: ssh -i your-key.pem ec2-user@<public-ip>.  
Security Groups serve as a virtual firewall that allows only the right traffic to your instances.  

# Networking Commands

I performed a number of basic networking commands, which are pretty important in terms of debugging and monitoring networks:

Networking Commands
----

**ping:** Verify if a connection is present between two devices.  
Usage: ping google.com  

**traceroute / tracert:** Show which route the packets will take to get to the destination.  
Usage: traceroute google.com  

**netstat:** Prints out network statistics.  
Usage: netstat -an  

**curl:** HTTP requests  
Usage: curl http://example.com  

**dig / nslookup:** Resolve DNS.  
Usage: dig google.com or nslookup google.com  

--------------------------------------------
This week has been a great introduction to foundational networking concepts and tools. Stay tuned for Week 2 as we dive deeper into more exciting DevOps challenges!

