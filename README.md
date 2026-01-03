# Cybersecurity Lab: SMB Enumeration & Website Cloning (Kali Linux)

This repository documents two cybersecurity labs I completed using Kali Linux:
1️⃣ SMB (Server Message Block) Enumeration & Analysis  
2️⃣ Website Cloning & Credential Harvesting using Social Engineering Toolkit (SET)

The purpose of these labs is to understand attacker methodologies, strengthen defensive awareness, and apply practical cybersecurity skills in a controlled learning environment.

---

## Lab 1: SMB Enumeration

### 🎯 Objective
To perform reconnaissance and enumeration on a target system to identify exposed SMB services, users, shares, password policies, and potential security weaknesses.

### 🛠️ Tools Used
- Kali Linux
- Nmap
- enum4linux

---

## 📸 Screenshots

### 🔍 Nmap Scan – Discovering SMB Ports (139 & 445)
![Nmap Scan]<img width="975" height="473" alt="image" src="https://github.com/user-attachments/assets/a4531dae-193e-4895-a412-5f443890b82a" />


### 👤 Enumerating Users
![User Enumeration]<img width="975" height="439" alt="image" src="https://github.com/user-attachments/assets/192d85fa-8ee1-4b30-9d6a-037af085fe61" />
<img width="975" height="401" alt="image" src="https://github.com/user-attachments/assets/5291b41d-4e9e-499f-9ddd-7fd9a8c56e8d" />
<img width="975" height="509" alt="image" src="https://github.com/user-attachments/assets/f6814d8d-2a6f-4237-80b7-75a3b62ec1a9" />
<img width="975" height="434" alt="image" src="https://github.com/user-attachments/assets/a950e7fe-2cfd-4b21-948a-bac5ba88be26" />

### 📂 Enumerating SMB Shares
![Shares Enumeration]<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/25a66f16-346b-4566-8063-8a1829afc18c" />
<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/366a9205-4c4c-40b2-974a-ad147eedd45e" />

### 🏷️ Domain & Groups Enumeration
![Domain Info]<img width="975" height="448" alt="image" src="https://github.com/user-attachments/assets/32de7fed-31b3-4fe7-b463-d130fb0622d7" />
<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/4b0420eb-eb3c-47e4-bc2e-f9f5608980aa" />

### 🔐 Password Policy Enumeration
![Password Policy]<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/cfb0878f-7829-45e4-ac86-6a2ead1260a6" />
<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/dd1eb660-187e-4a04-84e7-e2db2e5ee557" />
<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/2dba18b2-996b-4c56-8f59-cf7e39053345" />

## 🎭 Payload Deployment & File Masquerading from virus.exe to group_work.txt
<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/10f9e718-4e8d-49fb-85c3-5ba858cafe60" />

## 🧠 Key Learning Outcomes
✔️ Understanding SMB as a critical network sharing protocol  
✔️ Performing enumeration to gather intelligence  
✔️ Identifying weak security configurations  
✔️ Importance of strong password policies and SMB hardening  

---

# 🌐 Lab 2: Website Cloning & Credential Capture

### 🎯 Objective
To demonstrate how attackers create a fake copy of a legitimate website to capture user credentials, highlighting phishing and social engineering risks.

### 🛠️ Tools Used
- Kali Linux
- Social Engineering Toolkit (SET)
- DVWA (for lab)

---

## 📸 Screenshots

### 🛠️ Launching Social Engineering Toolkit
![SET Menu]<img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/3f4897b9-60bd-4c0f-b4f7-e4499e8e70fb" />

### 🌐 Selecting Website Cloning Option
![SET Website Clone]<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/ea8a8073-d156-421d-9b39-8de00147d158" />
<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/4c3ffda8-a964-4347-881c-28ff7b6c6e77" />
<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/4248779c-736b-4e9a-9f00-30580619d0cd" />

### 🧬 Entering Target Website Details (ip address and url)
![Input Website]<img width="975" height="466" alt="image" src="https://github.com/user-attachments/assets/92f701e0-1e98-48b1-b1f9-accec345c919" />
<img width="975" height="381" alt="image" src="https://github.com/user-attachments/assets/637065db-4a12-48f3-b222-888db6536b40" />

### 🧪 Original vs Cloned Website
![Original vs Clone]<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/768d4046-6799-4edb-a482-9b2b5a907512" />
<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/d787ecd0-4447-45a8-9791-6651edeccee2" />

### 🔓 Credentials Captured
![Credentials Captured]<img width="975" height="506" alt="image" src="https://github.com/user-attachments/assets/94ea3abc-7a1c-4d7c-ab8b-d33c6c121aac" />
<img width="1920" height="997" alt="VirtualBox_Ethical-Hacker-Kali_22_12_2025_06_51_05" src="https://github.com/user-attachments/assets/7b7c762e-c97f-4191-9c40-13ebe1db1923" />
---

## 🧠 Key Learning Outcomes
✔️ How phishing pages are built and deployed  
✔️ Understanding credential harvesting techniques  
✔️ Importance of user awareness & URL verification  
✔️ Why security policies and training matter  

---

## 🔐 Ethical Use Notice
These labs were conducted in a **secured and controlled learning environment** strictly for educational and ethical cybersecurity learning purposes.  
They should never be used for malicious activity.

---
Thank you for taking your time to view my work.
