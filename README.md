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

<img width="482" height="281" alt="new run the setup 1" src="https://github.com/user-attachments/assets/b2b7f06e-6ba4-4449-b6af-6cc95d525377" />

<img width="448" height="343" alt="run the setup 2" src="https://github.com/user-attachments/assets/53cd31cc-82c9-47ce-93c4-f5e61e5e3bb4" />

<img width="476" height="349" alt="run the setup 3" src="https://github.com/user-attachments/assets/dad0a632-711a-405a-b64c-dbb2e02bede9" />

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

<img width="476" height="269" alt="Screenshot 2026-09-22 194123" src="https://github.com/user-attachments/assets/e39623c4-fc8f-4c85-8dd5-86675b44cfff" />

<img width="476" height="338" alt="paste hash 1" src="https://github.com/user-attachments/assets/f2abf182-d109-45ea-a6d0-8517e3a2d5a6" />


### Step 5: 

* Open Johnny and Click on ‘Open password file’, Browse the hash value file and upload it.

<img width="503" height="233" alt="Screenshot 2026-09-22 194226" src="https://github.com/user-attachments/assets/6d9c05a3-3c18-4207-99b4-5e7fc97eadec" />

<img width="503" height="232" alt="Screenshot 2026-09-22 194250" src="https://github.com/user-attachments/assets/fe22d6dc-34f1-411b-9392-aa7628deab78" />

* Put the password you get after uploading the file to open the Locked PDF.

<img width="374" height="313" alt="Screenshot 2026-09-22 194517" src="https://github.com/user-attachments/assets/bd0f477d-baf4-4526-9ebb-e1cc6fe3c931" />

<img width="409" height="313" alt="Screenshot 2026-09-22 194632" src="https://github.com/user-attachments/assets/d4d222a2-f615-4e66-8c7d-017fa4ce5f96" />

---

### Other Pdfs

We can get the passwords of other pdfs too in the similar way.

#### Locked PDF 1:

* Get the hash value of the pdf by uploading it via browse option in the PDF hash Extractor - instantly. 
<img width="640" height="377" alt="Screenshot 2026-09-22 194041" src="https://github.com/user-attachments/assets/36596fdc-7fb5-45b9-8ab5-416c99a7a38e" />

* Then make a file of that hash value from Notepad.
<img width="476" height="338" alt="paste hash 1" src="https://github.com/user-attachments/assets/0f41d986-f4a9-465d-87d4-115f63d1a0c5" />

* Upload the hash value file in the Johnny GUI and get the password.
<img width="473" height="287" alt="Screenshot 2026-09-22 211419" src="https://github.com/user-attachments/assets/6f26ada8-b483-43cf-9795-3e03018f0e81" />

* Use the password to unlock the pdf.
<img width="409" height="313" alt="Screenshot 2026-09-22 194632" src="https://github.com/user-attachments/assets/9a6c19b5-88cc-48c9-a83a-18b0cbaa3ad7" />

#### Locked PDF 2: 

* Get the hash value of the pdf by uploading it via browse option in the PDF hash Extractor - instantly. 
<img width="629" height="333" alt="Screenshot 2026-09-22 210401" src="https://github.com/user-attachments/assets/a2459f51-fc7b-4954-8ca0-1f90c2ae11d3" />

* Then make a file of that hash value from Notepad.
<img width="473" height="327" alt="paste hash 2" src="https://github.com/user-attachments/assets/8c61bb4b-0811-4088-9839-c0c2691399ac" />


* Upload the hash value file in the Johnny GUI and get the password.
<img width="473" height="287" alt="Screenshot 2026-09-22 211419" src="https://github.com/user-attachments/assets/b16e0a5d-5676-4d50-9ddd-992d5fb10b12" />

* Use the password to unlock the pdf.
<img width="632" height="317" alt="Screenshot 2026-09-22 211502" src="https://github.com/user-attachments/assets/bf4a9b07-dc57-4954-84df-76f1e91fa3fd" />

#### Locked PDF 3: 

* Get the hash value of the pdf by uploading it via browse option in the PDF hash Extractor - instantly. 
<img width="635" height="333" alt="Screenshot 2026-09-22 211628" src="https://github.com/user-attachments/assets/d9524391-5d25-4260-9da5-471de09e5b46" />

* Then make a file of that hash value from Notepad.
<img width="475" height="329" alt="paste hash 3" src="https://github.com/user-attachments/assets/2cd6f73b-bfaf-403e-a452-df4517c68e0f" />


* Upload the hash value file in the Johnny GUI and get the password.
<img width="638" height="374" alt="Screenshot 2026-09-22 211743" src="https://github.com/user-attachments/assets/e042f6f0-cc2c-465e-89d5-351d4b550cec" />

* Use the password to unlock the pdf.
<img width="410" height="314" alt="Screenshot 2026-09-22 211848" src="https://github.com/user-attachments/assets/7e47ccaa-bfa0-491f-8501-06b26c8cd3b9" />

---

## 🎓 What I Learned

John the Ripper (JTR) and Johnny GUI are primary security tools used for password cracking and security auditing:

* John the Ripper (JTR):

A powerful, command-line password cracking tool designed to detect weak or compromised passwords. It tests hashed and encrypted passwords against dictionary attacks, brute-force attacks, and custom mask/rule sets. Security professionals and system administrators use it to audit password strength and enforce robust security policies.

* Johnny GUI:

  An open-source Graphical User Interface (GUI) for John the Ripper. Because JTR operates entirely via terminal commands—which can have a steep learning curve—Johnny provides an intuitive, user-friendly interface. It allows users to run JTR sessions, configure attack modes, and manage hash lists using visual buttons and menus without needing to type complex command-line syntax.

  ---
  
# Project Module 2

Password cracking with NetworkWalks tools.

## 🎯 Objectives

Step 1: Get the hash value from Networkwalks Hash Calculator.

Step 2: Crack the password od pdf with Networkwalks Password Cracker.

---

### Step 1: 

* Download the encrypted PDF file (My Locked PDF1.pdf) to your laptop from the lab page:

```bash
https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/
```
<img width="629" height="334" alt="Screenshot 2026-09-23 093530" src="https://github.com/user-attachments/assets/c17f30ae-1edc-4a9b-bb36-4eddc802b75d" />

* Open the Networkwalks Hash Calculator in your web browser:

```bash
https://networkwalks.com/hash-calculator/
```
<img width="631" height="334" alt="Screenshot 2026-09-23 093052" src="https://github.com/user-attachments/assets/9f4d7bcb-6823-4f42-ba4e-e0811fab0ff1" />

* Upload the locked PDF file to the Hash Calculator. The tool will read the file and give you the hash
value that starts with $pdf$..., copy the full hash value.
<img width="638" height="334" alt="Screenshot 2026-09-23 093148" src="https://github.com/user-attachments/assets/a9b1e7dc-4065-4b38-8f3b-a708566c32b1" />

<img width="625" height="335" alt="Screenshot 2026-09-23 093215" src="https://github.com/user-attachments/assets/f0a89ee0-f2cb-454a-bc33-2e988f83d7f1" />

### Step 2: 

* Open the Networkwalks Password Cracker in your web browser:

```bash
https://networkwalks.com/password-cracker/
```
<img width="627" height="332" alt="Screenshot 2026-09-23 093242" src="https://github.com/user-attachments/assets/27410475-acee-4a75-abd9-934eceee959d" />

* Paste the hash value into the Password Cracker and start the attack. Wait for the tool to finish. The cracked password will be shown on the screen.
<img width="626" height="334" alt="Screenshot 2026-09-23 093309" src="https://github.com/user-attachments/assets/7914328a-5d0f-4f3b-8eab-a2409b400c56" />

* Open the locked PDF file and enter the cracked password.
<img width="626" height="332" alt="Screenshot 2026-09-23 093335" src="https://github.com/user-attachments/assets/3c297615-f732-418f-b83c-99780b115874" />

<img width="409" height="313" alt="Screenshot 2026-09-22 194632" src="https://github.com/user-attachments/assets/2f4e6417-89bf-4c33-8f34-230d1e160d02" />

---

### Other PDFs

#### Locked PDF 1:

* Get the hash value from Networkwalks Hash Calculator.
<img width="625" height="335" alt="Screenshot 2026-09-23 093215" src="https://github.com/user-attachments/assets/07bb35ed-5840-4b17-a129-32e0a808542b" />

* Paste the hash value into the Password Cracker and start the attack to crack password.
<img width="626" height="332" alt="Screenshot 2026-09-23 093335" src="https://github.com/user-attachments/assets/b4f5d733-b634-426d-ade8-ee3991b5f813" />

* Use the cracked password to oprn the locked pdf.
<img width="409" height="313" alt="Screenshot 2026-09-22 194632" src="https://github.com/user-attachments/assets/c1e9a5eb-7182-4440-997f-6cba592b3053" />

#### Locked PDF 2: 

* Get the hash value from Networkwalks Hash Calculator.
<img width="628" height="331" alt="Screenshot 2026-09-23 093913" src="https://github.com/user-attachments/assets/d200e8a1-93bb-4f07-a169-8c681b0f708a" />

* Paste the hash value into the Password Cracker and start the attack to crack password.
<img width="626" height="335" alt="Screenshot 2026-09-23 094023" src="https://github.com/user-attachments/assets/d0078d6e-06be-4055-a3c0-f0f8f1bb9efa" />

* Use the cracked password to oprn the locked pdf.
<img width="632" height="317" alt="Screenshot 2026-09-22 211502" src="https://github.com/user-attachments/assets/a0822b28-1fc8-4733-93ed-33e184b71879" />

#### Locked PDF 3:

* Get the hash value from Networkwalks Hash Calculator.
<img width="626" height="337" alt="Screenshot 2026-09-23 094117" src="https://github.com/user-attachments/assets/fdc194c5-0668-4467-bd1d-b62af726bea1" />

* Paste the hash value into the Password Cracker and start the attack to crack password.
<img width="628" height="329" alt="Screenshot 2026-09-23 094154" src="https://github.com/user-attachments/assets/43b3671b-3be2-4253-80b5-416d4da5a6f6" />

* Use the cracked password to oprn the locked pdf.
<img width="410" height="314" alt="Screenshot 2026-09-22 211848" src="https://github.com/user-attachments/assets/7619a8bd-d2cb-48ae-8102-4148b243017a" />

---

## 🎓 What I Learned 

* Password cracking is the process of recovering a password from stored data or a protected file. Security
professionals use it to test how strong a password is and to show why weak passwords are risky. If a
password is short or common, it can be found quickly, which proves the need for strong passwords.

* Many files like PDF, ZIP, and Office documents can be locked with a password. When a file is locked, its
password is stored in the form of a hash. A hash is a scrambled value that represents the password. To
recover the password, we first take out this hash from the file, and then run it through a cracking tool that
tries different words until it finds a match.

* In this module we used two free online tools made by Networkwalks. First we used the Hash Calculator
to take the hash out of a locked PDF file. Then we will use the Password Cracker to find the real password
from that hash value. Both tools run in the web browser, so one do not need to install anything.

---

## 🏹 Tools and Resources 

### 1. Password Cracking Frameworks

* **John the Ripper (JTR):** A powerful command-line password cracking tool used for security auditing and password recovery. It tests hashed passwords against dictionary lists, brute-force patterns, and rule sets to uncover weak passwords.
  
* **Johnny GUI:** An open-source Graphical User Interface (GUI) wrapper for John the Ripper. It simplifies the JTR workflow by providing a visual interface to manage hash files, configure attack parameters, and monitor cracking sessions without running raw terminal commands.

### 2. Networkwalks Online Security Tools

* **Networkwalks Hash Calculator:** A web-based utility used during initial target preparation to extract and generate password hash values directly from protected files (such as password-locked PDFs and archives).
  
* **Networkwalks Password Cracker:** A lightweight, browser-based online cracking tool designed to process extracted hash strings and test wordlists to recover original plaintext passwords.

---

## 🔗 Important Links & Resources

### 1. Installation & Local Tools

* **[Download John the Ripper (Official Website)](https://www.openwall.com/john/)** – Download the JTR password cracking tool binaries for Windows/Linux/macOS.

```bash
https://distro.ibiblio.org/openwall/projects/john/1.9.0/
```
* You can download from Google Drive:
  
```bash
https://drive.google.com/drive/u/1/folders/1aHtgOh7U9mQhkN8VHU7ctTyaDg5KbuJx
```

* **[Download Johnny GUI (Official Page)](https://openwall.info/wiki/john/johnny)** – Download the graphical user interface wrapper for John the Ripper.

* You can download from Google Drive:
 ```bash
https://drive.google.com/drive/u/1/folders/1aHtgOh7U9mQhkN8VHU7ctTyaDg5KbuJx
```

### 2. File Preparation & PDF Utilities

* **[Sample Locked PDF Downloads](https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/)** – Resource to download sample target PDF files and lock/encrypt them with passwords for testing.
  
* **[Instant Online PDF Hash Extractor](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php)** – Extract hash signatures directly from password-protected PDF files in your browser.

### 3. Networkwalks Web Applications

* **[Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator/)** – Access the browser-based Networkwalks Hash Calculator tool.
  
* **[Networkwalks Password Cracker](https://networkwalks.com/password-cracker/)** – Access the browser-based Networkwalks Password Cracker tool.

---



















