# 🔐 PDF Password Auditing with John the Ripper

<p align="center">

**NetworkWalks | Cybersecurity & Ethical Hacking**

*Week 3 Practical Exercise*

</p>

<p align="center">

![John the Ripper](https://img.shields.io/badge/Tool-John%20the%20Ripper-red?style=for-the-badge)
![Password Auditing](https://img.shields.io/badge/Focus-Password%20Auditing-blue?style=for-the-badge)
![Training](https://img.shields.io/badge/Training-NetworkWalks-purple?style=for-the-badge)

</p>

## 📌 Project Overview

This repository documents my practical exercise on PDF password auditing using **John the Ripper** as part of the NetworkWalks Cybersecurity & Ethical Hacking training programme.

The exercise involved extracting password hashes from password-protected PDF training files, importing the extracted hashes into Johnny (the graphical interface for John the Ripper), and performing dictionary-based password recovery.

## 🎯 Objectives

- Understand how password-protected PDF files can be prepared for password auditing.
- Extract password hashes from authorised PDF training documents.
- Learn how John the Ripper processes password hashes.
- Perform dictionary-based password recovery.
- Verify recovered passwords against the corresponding training PDFs.

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| John the Ripper | Password auditing and recovery |
| Johnny GUI | Graphical interface for John the Ripper |
| Online Hash Crack | PDF password hash extraction |
| PDF files | Authorised training samples |

## ⚙️ Practical Workflow

### 1. PDF Hash Extraction

Used an online PDF hash extraction utility to extract the password hash from an encrypted training PDF.

### 2. Hash Preparation

Saved the extracted hash in a text file for use with John the Ripper.

### 3. Password Auditing with Johnny

Imported the hash into Johnny and performed a dictionary-based password recovery attack.

### 4. Verification

Used the recovered password to verify access to the corresponding protected training PDF.

## 🔄 Workflow

`Protected PDF → Hash Extraction → Hash File → Johnny / John the Ripper → Dictionary Attack → Verification`

## 📸 Evidence

The screenshots folder contains selected evidence from the practical:

- PDF hash extraction.
- Hash file preparation.
- Johnny interface and imported hash.
- Password recovery result.
- Successful PDF access verification.

Sensitive passwords, hashes and private document information have been redacted from public evidence.

## 📚 Key Learning Outcomes

- Understanding PDF password hashes.
- Preparing extracted hashes for password auditing.
- Using John the Ripper and Johnny.
- Understanding dictionary-based attacks.
- Recognising the risks of weak passwords.
- Verifying password recovery results.

## 🛡️ Ethical Considerations

This exercise was conducted for educational purposes using authorised training materials. Password auditing should only be performed on files or systems that you own or have explicit permission to assess.

No recovered passwords or reusable password hashes are published in this repository.

## 🎓 Training Details

- **Programme:** NetworkWalks – Cybersecurity & Ethical Hacking
- **Week:** Week 3
- **Project:** PDF Password Auditing
- **Primary Tool:** John the Ripper
- **Interface:** Johnny

---

<p align="center">

**Learning by doing. Building practical cybersecurity skills. 🚀**
<img width="1022" height="741" alt="Screenshot 2026-11-17 143440" src="https://github.com/user-attachments/assets/fc458fbf-26d5-41cc-b15b-879bcb47a776" />
<img width="1136" height="828" alt="Screenshot 2026-11-17 140837" src="https://github.com/user-attachments/assets/f11e5e42-bb05-406f-95d9-4ad565b268d5" />
<img width="1301" height="965" alt="Screenshot 2026-11-17 133814" src="https://github.com/user-attachments/assets/0be09118-2519-4425-aebf-cdc81b55ed39" />

</p>
