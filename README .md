# Minor 2 – Metasploitable & Mutillidae II

## Student Details
- **Name:** Ayush Kumar Singh
- **Course:** B.Tech CSE (Core)

## 🎯 Project Objective
To install Metasploitable in a virtualized environment on Kali Linux and fix the Mutillidae II database error.

## 🛠 Tools Used
- VirtualBox
- Metasploitable2

## 🚀 Steps Performed
1. Installed VirtualBox on Kali Linux
2. Imported Metasploitable2 VM
3. Created a new user inside Metasploitable
4. Took snapshot after user creation
5. Fixed Mutillidae II database error
6. Verified application working successfully

## 💻 Commands Used
```bash
sudo useradd -m A.k.sINGH
sudo passwd A.k.sINGH
sudo service mysql start
sudo chmod -R 777 /var/www/mutillidae
mysql -u root
CREATE DATABASE mutillidae;
```

## 📸 Proof
Screenshots are included in the repository as evidence.

## ✅ Status
Project completed successfully.

