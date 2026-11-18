# Week 3: Password Cracking and Hashing (Networkwalks & John the Ripper)

This repository contains practical coursework and task documentation for **Week 3 (Project Module 1 & 2)** of the Cybersecurity & Ethical Hacking training program.

## 📌 Project Overview
The objective of this practical exercise was to understand password security auditing, hash extraction, and password recovery techniques using a password-protected PDF file (`My Locked PDF1.pdf`).

## 🛠️ Tools & Environment
* **Operating System:** Windows 11 PC
* **Password Cracking Engines:** John the Ripper & Johnny GUI
* **Online/Platform Tools:** Online HashCrack, Networkwalks Hash Calculator, and Networkwalks Password Cracker

---

## 📋 Tasks Performed

### Task 1: Installation and Configuration of John the Ripper (Johnny GUI)
* Installed and configured John the Ripper along with its graphical user interface (**Johnny**) on Windows 11.
* Explored password auditing features, hash identification, and dictionary/brute-force attack configurations

### Task 2: Password Hash Identification and Cracking (Johnny)
1. **Hash Extraction:** Extracted the password hash from the encrypted PDF file (`My Locked PDF1.pdf`).
2. **Hash File Creation:** Saved the extracted hash into a text file named `hash.txt`
3. **Cracking Execution:** Loaded the hash into Johnny GUI and initiated password recovery.
4. **Verification:** Successfully recovered the password (`password1`) and unlocked the target PDF file.

### Task 3: Password Cracking Using Networkwalks Tools
1. Utilized **Networkwalks Hash Calculator** to parse the encrypted PDF locally and extract the crackable hash (`pdf2john / hashcat` compatible format)
2. Ran **Networkwalks Password Cracker** to perform dictionary-based password recovery.
3. Captured the completion flag (`nw{networkwalks_flag1_jtr_270521_1}`) upon successful verification.

---

## 🔒 Learning Outcomes
* Gained hands-on experience in distinguishing between file decryption and password hash cracking.
* Understood how weak passwords leave sensitive documents vulnerable and why robust password policies are essential.
