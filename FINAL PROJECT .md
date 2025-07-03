 Building a Virtual Cybersecurity Laboratory and Conducting Android Forensics

1 PROJECT SCOPE:- Virtual Cybersecurity Lab Setup
Objective: 
To simulate a secure, real-world environment for offensive and defensive security testing through virtual machines. 
Activities: 
● Install a Type 2 hypervisor (e.g., VirtualBox, VMware Workstation/Player)
● Create and configure two virtual machines:
● Kali Linux (attacker environment)
● Microsoft Windows 7 or 10 (target environment)
● Establish internal virtual networking between VMs
● Verify connectivity via ping tests, shared directories, and service enumeration


Could you set up an internal network between Kali Linux and Windows VMs so they can talk to each other privately?

Network
network name- lab

subnet-255.255.255.0

kalilab - 192.168.10.10

Windows - 192.168.10.11



2: PROJECT SCOPE: Conducting Android Forensics

Investigations

---

## 📄 Case Information

*Case Title:* DSA FORENSIC PROJECT
*Case Number:* 007  
*Date:* July 03, 2025  
*Prepared By:*Emmanuel Odunsi
*Affiliation/Agency:* V Lab 

---

## 📌 Executive Summary

This report presents the forensic analysis of an Android device image in ISO format. The image was processed using Autopsy, and key artifacts such as chat data, browsing history, and media metadata were recovered. The investigation focused on potential evidence of communication, location history, and deleted files.

---

## 🎯 Scope & Objectives

- To examine the contents of an Android image file (android_image.iso)
- To identify and extract user data such as messages, contacts, and images
- To recover deleted files and analyze media metadata
- To provide a summarized forensic overview for legal or investigative use

---

## 🔧 Tools Used

Autopsy Version:	4.22.1
Android Analyzer Module:	4.22.1
Android Analyzer (aLEAPP) Module:	4.22.1


| Tool        | Version  | Purpose                     |
|-------------|----------|-----------------------------|
| Autopsy     | 4.21.0   | Forensic analysis           |
| Windos11  | 2024.4   | Host Operating System       |
| Sleuth Kit  | 4.12.1   | Backend processing engine   |
| 7zp      | Built-in | ISO to DD image conversion  |

---

## 🧪 Methodology

1. Received and verified the Android .iso file using SHA256 hashing.
2. Converted .iso to .dd format using dd command.
3. Loaded image into Autopsy as a disk image.
4. Scanned for web artifacts, images, app data, and deleted content.
5. Tagged and bookmarked relevant findings.
6. Exported final report and screenshots.

