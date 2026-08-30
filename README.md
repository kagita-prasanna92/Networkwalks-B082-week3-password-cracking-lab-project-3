# Networkwalks-B082-week3-password-cracking-lab-project-3
In this project, I performed a hands-on password-cracking lab using John the Ripper (JTR) and Johnny. The objective was to understand password hash extraction and password recovery techniques in an authorized lab environment. This activity helped me understand the risks of weak passwords and the importance of strong password security

---

## 📌 Project Overview

As part of the **NetworkWalks Cybersecurity Internship — Batch B082, Week 03**, I performed a practical password-security lab using intentionally provided password-protected PDF files.

The lab focused on understanding how a password-protected PDF can be processed into a crackable hash representation and how password-recovery tools can be used in an **authorized educational environment**.


##  Objectives

- Understand password-protected PDF files.
- Learn the role of password hashes in password-security testing.
- Configure and use **John the Ripper / Johnny**.
- Extract a PDF hash in a compatible format.
- Perform dictionary-based password testing in a controlled lab.
- Verify the recovered password against the provided PDF.
- Understand the importance of strong and unique passwords.
- Document practical cybersecurity work with screenshots and evidence.

---

##  Ethical & Authorized Use

>  **AUTHORIZED EDUCATIONAL LAB ONLY**
>
> All activities documented in this repository were performed for cybersecurity learning and practical training using intentionally provided laboratory material.
>
> Password-recovery techniques should only be used on files, systems, or accounts for which you have explicit authorization.

---

#  Lab Environment

| Component | Details |
|---|---|
| Operating System | Windows |
| Primary Password Tool | John the Ripper / Johnny |
| Secondary Tools | NetworkWalks Hash Calculator & Password Cracker |
| Target | Password-protected PDF |
| Attack Method | Dictionary-based password testing |
| Environment | Authorized educational laboratory |

---

#  Tools Used

###  John the Ripper / Johnny
Used to work with password hashes and perform password-recovery testing.

###  NetworkWalks Hash Calculator
Used to process the password-protected PDF and extract a compatible PDF hash.

###  NetworkWalks Password Cracker
Used to perform dictionary-based password testing against the extracted PDF hash.

###  PDF Reader
Used to verify that the recovered password successfully unlocks the protected PDF.

---

#  Practical Workflow

```text
              Authorized Lab File
                     │
                     ▼
             Password-Protected PDF
                     │
                     ▼
                Hash Extraction
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
   John the Ripper        NetworkWalks Tools
      / Johnny             Hash Calculator
          │                     │
          ▼                     ▼
     Password Hash        PDF Hash Output
          │                     │
          ▼                     ▼
   Password Testing      Password Cracker
          │                     │
          └──────────┬──────────┘
                     ▼
             Password Verification
                     │
                     ▼
               Flag / Result
```

---

#  W3-PM1 — John the Ripper / Johnny

## 1. John the Ripper Configuration

Johnny was configured to use the installed **John the Ripper Jumbo** executable.

The configuration screen confirms that the JTR executable was detected successfully.

### 📸 Password cracked 
<img width="1028" height="622" alt="Screenshot 2026-08-30 111819" src="https://github.com/user-attachments/assets/830a2725-5260-428d-9984-eb3a33b27569" />
<img width="988" height="620" alt="Screenshot 2026-08-30 111741" src="https://github.com/user-attachments/assets/e477a61d-61d6-4e59-810d-7b7b38ccc6d8" />

---

#  W3-PM2 — PDF 

## 2. Extracting the PDF Hash

The password-protected PDF was processed using a PDF hash-extraction tool.

The resulting output was presented in a format compatible with password-auditing tools such as **John the Ripper** and **Hashcat**.

### 📸 Password cracked 

<img width="979" height="621" alt="Screenshot 2026-08-30 113020" src="https://github.com/user-attachments/assets/3007634e-c29a-4d2b-b23a-fd8d3f8d410c" />
<img width="472" height="585" alt="Screenshot 2026-08-30 112948" src="https://github.com/user-attachments/assets/372fe8d4-4a7f-44f7-98d4-9af55acf6262" />

---

#  NetworkWalks Hash Calculator

## 3. Hash Calculator

The NetworkWalks Hash Calculator was used to analysed the protected PDF and generate a crackable PDF hash representation.

The tool identified the PDF as encrypted and displayed the extracted hash.

### 📸 Password cracked 

<img width="988" height="567" alt="Screenshot 2026-08-30 113508" src="https://github.com/user-attachments/assets/54a6f708-a98a-4fbb-9246-ab5b3858c7a6" />
<img width="953" height="623" alt="Screenshot 2026-08-30 113450" src="https://github.com/user-attachments/assets/ad9e75f6-9183-48a9-b11b-abe25a5067e9" />
<img width="548" height="536" alt="Screenshot 2026-08-30 113422" src="https://github.com/user-attachments/assets/bda419f2-4c28-4e05-ae99-082763243d61" />


---

#  NetworkWalks Password Cracker

## 4. Dictionary-Based Password Testing

The extracted PDF hash was supplied to the NetworkWalks Password Cracker.

The tool tested candidate passwords from a dictionary and identified a successful match.

### 📸 Crack the password 



### ✅ Result

**Password successfully recovered in the authorized lab environment.**
<img width="548" height="536" alt="Screenshot 2026-08-30 113422" src="https://github.com/user-attachments/assets/955dd26d-2133-4c5e-b045-c10f711d96a1" />


> For security and responsible-publication purposes, the recovered password is intentionally not reproduced in this README.

---

#  PDF Verification & Flag

## 5. Password Verification

After successful password recovery, the protected PDF was opened and verified.

The lab PDF displayed a successful completion message and a captured flag.

---

#  Practical Results

| Activity | Status |
|---|---|
| John the Ripper / Johnny configuration | ✅ Completed |
| PDF hash extraction | ✅ Completed |
| NetworkWalks Hash Calculator | ✅ Completed |
| Dictionary-based password testing | ✅ Completed |
| Password recovery | ✅ Successful |
| PDF verification | ✅ Completed |
| Lab flag captured | ✅ Successful |
| Evidence documentation | ✅ Completed |

---

#  Key Learning Outcomes

Through this practical, I gained hands-on understanding of:

-  Password security
-  PDF hash extraction
-  Hash formats
-  John the Ripper / Johnny
-  Dictionary-based password testing
-  Security-tool configuration
-  Password-protected PDF analysis
-  Practical password auditing
-  Evidence collection
-  Cybersecurity documentation
-  Ethical security testing

---

#  Password Security Takeaways

### 1. Use Strong Passwords
Simple and predictable passwords are more susceptible to dictionary-based recovery.

### 2. Avoid Password Reuse
Using the same password across multiple resources increases the potential impact of password compromise.

### 3. Protect Password Hashes
Password hashes should be treated as sensitive security information because they may be targeted by offline password-recovery techniques.

### 4. Test Only With Authorization
Password auditing should only be performed against systems or files where explicit permission has been granted.

---

# 📂 Repository Structure

```text
networkwalks-B082-week3-password-cracking/
│
├── README.md
│
└── screenshots/
    ├── 01-johnny-john-the-ripper-configuration.png
    ├── 02-pdf-hash-extraction.png
    ├── 03-networkwalks-hash-calculator.png
    ├── 04-networkwalks-password-cracker.png
    └── 05-pdf-flag-verification.png
```

---

#  Conclusion

This Week 03 practical provided valuable hands-on experience with **password security, PDF hash extraction, John the Ripper / Johnny, dictionary-based password testing, and password verification**.

The lab helped strengthen my understanding of how password-protected files can be assessed in a controlled cybersecurity environment and why organizations should use strong, unique and unpredictable passwords.

---

##  NetworkWalks Cybersecurity Internship

**Batch:** B082  
**Week:** 03  
**Focus:** Password Security & Password Cracking

 *Learning cybersecurity through practical, authorized hands-on exercises.*
