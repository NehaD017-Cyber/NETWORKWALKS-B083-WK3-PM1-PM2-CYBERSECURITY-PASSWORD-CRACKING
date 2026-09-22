# NETWORKWALKS-B083-WK3-PM1-PM2-CYBERSECURITY-PASSWORD-CRACKING
In this project, we're going to learn about password cracking with JTR (John the Ripper) and with the Networkwalks tools. 

# PASSWORD CRACKING

In this project, we have to learn how to crack the password of any pdf with the help of John the Ripper and with the NetworkWalks tools. 

In this project we will go through two project modules:

* PM1: Password Cracking with JTR
  
* PM2: Password Cracking with NW Tools

  <!-- Core Security & Modules -->
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Shield-007ACC?style=for-the-badge&logo=cyberdefenders&logoColor=white)
![Ethical Hacking](https://img.shields.io/badge/Ethical_Hacking-Offensive-red?style=for-the-badge&logo=kalilinux&logoColor=white)
![Penetration Testing](https://img.shields.io/badge/Penetration_Testing-Pentest-107C41?style=for-the-badge&logo=hackthebox&logoColor=white)
![Network Walks](https://img.shields.io/badge/Network_Walks-Traffic_Analysis-6f42c1?style=for-the-badge&logo=wireshark&logoColor=white)
![Network Walks Tools](https://img.shields.io/badge/Network_Walks_Tools-Recon_%26_Audit-FF6F00?style=for-the-badge&logo=nmap&logoColor=white)

<!-- Cracking & Authentication -->
![Password Cracking](https://img.shields.io/badge/Password_Cracking-Brute_Force-D13438?style=for-the-badge&logo=1password&logoColor=white)
![John the Ripper](https://img.shields.io/badge/JTR-John_The_Ripper-4E2A84?style=for-the-badge&logo=gnu-privacy-guard&logoColor=white)

<!-- Environment & Tools -->
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)
![Virtualization](https://img.shields.io/badge/Virtualization-VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)
![Visualization](https://img.shields.io/badge/Visualization-Metrics_%26_Logs-00C7B7?style=for-the-badge&logo=grafana&logoColor=white)

<!-- Recommended Additions -->
![Kali Linux](https://img.shields.io/badge/OS-Kali_Linux-557C93?style=for-the-badge&logo=kalilinux&logoColor=white)
![Nmap Scan](https://img.shields.io/badge/Scanning-Nmap-2B579A?style=for-the-badge&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Packet_Analysis-Wireshark-167DA4?style=for-the-badge&logo=wireshark&logoColor=white)
![Bash Scripting](https://img.shields.io/badge/Automation-Bash_Scripting-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

## 🔎 Project Overview

This project focuses on practical cybersecurity techniques, network traffic auditing, and password security analysis within an isolated lab environment. By leveraging John the Ripper (JTR) for password hash recovery and NetworkWalks tools this study demonstrates how vulnerabilities are identified, assessed, and mitigated in modern network infrastructure.

---

# PROJECT MODULE 1

PASSWORD CRACKING WITH JTR

## 🎯 Objectives

Step 1: Download John the Ripper from official website on your windows PC.

Step 2: Download Johnny GUI from official website.

Step 3: Open PDF-HASH EXTRACTOR-INSTANTLY in the chrome and get the hash.

Step 4: Save the hash using notepad.

Step 5: Get the password of the pdf by uploading the hash file in the JTR.

---

### Step 1: 

* Use the link and download the John the Ripper from it's official side:

```bash
https://www.openwall.com/john/
```

OR

```bash
https://distro.ibiblio.org/openwall/projects/john/1.9.0/
```

OR

you can download from Google Drive:

```bash
https://drive.google.com/drive/u/1/folders/1aHtgOh7U9mQhkN8VHU7ctTyaDg5KbuJx
```

<img width="640" height="368" alt="Screenshot 2026-09-22 112322" src="https://github.com/user-attachments/assets/67ee324f-3190-4c66-b037-2fbbd24a1aac" />

### Step 2: 

* Download Johnny GUI from official website:

```bash
https://openwall.info/wiki/john/johnny
```

 OR
 
 you can download from Google Drive:

 ```bash
https://drive.google.com/drive/u/1/folders/1aHtgOh7U9mQhkN8VHU7ctTyaDg5KbuJx
```

<img width="640" height="366" alt="Screenshot 2026-09-22 120425" src="https://github.com/user-attachments/assets/af09e131-1dc7-4869-b47a-859cccb37258" />

* Run the setup file & install Johnny as shown in below:

<img width="482" height="281" alt="Screenshot 2026-09-22 113451" src="https://github.com/user-attachments/assets/b8c75e6f-990f-4033-a267-54f04f4589c9" />

<img width="448" height="343" alt="Screenshot 2026-09-22 113504" src="https://github.com/user-attachments/assets/7ce31438-ed5d-4ac8-950c-33d10038eafa" />

<img width="476" height="349" alt="Screenshot 2026-09-22 113519" src="https://github.com/user-attachments/assets/4d512eae-7a50-477a-a211-edbe6d44059a" />

* After installation, open Johnny and Click on settings & browse:

<img width="476" height="292" alt="Screenshot 2026-09-22 201508" src="https://github.com/user-attachments/assets/3f2ae67c-e85a-4ccf-9590-883e8c6c876f" />

### Step 3: 

* Open the hash website & upload your pdf file to find its hash value:

```bash
https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php
```
<img width="629" height="334" alt="Screenshot 2026-09-22 202000" src="https://github.com/user-attachments/assets/458d8b96-997a-4313-b52a-56a7c9566dbb" />

* Select the file from browse , upload it and copy the hash value.

<img width="638" height="376" alt="Screenshot 2026-09-22 121108" src="https://github.com/user-attachments/assets/55633dad-9939-49b1-adfd-ae4897cdaa32" />

   <img width="640" height="377" alt="Screenshot 2026-09-22 194041" src="https://github.com/user-attachments/assets/12f797eb-6ff0-4a43-9bd7-40b9d40c044e" />

### Step 4: 

* Paste the hash value in the notepad and save it.





### Step 5: 

* Open Johnny and Click on ‘Open password file’, Browse the hash value file and upload it.



* Put the password you get after uploading the file to open the Locked PDF.











