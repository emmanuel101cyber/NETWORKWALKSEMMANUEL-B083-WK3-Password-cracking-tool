# 🔐 Password Cracking with Networkwalks Tools

![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-blue)
![Lab](https://img.shields.io/badge/Type-Password%20Cracking-red)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)

## 📌 Project Overview

This project was completed as part of the **Networkwalks Cybersecurity & Ethical Hacking Internship – Week 3, Project Module 2**.

The objective was to understand password cracking by recovering passwords from three password-protected PDF documents using the Networkwalks Hash Calculator and Password Cracker.

The exercise demonstrated how password hashes can be extracted from protected PDF files, submitted to a password-cracking tool, and tested against candidate passwords until a match is identified.

The recovered passwords were subsequently used to access the protected documents and retrieve embedded laboratory flags.

---

## 🎯 Objectives

- Understand the fundamentals of password cracking.
- Extract password hashes from protected PDF documents.
- Use online password-cracking tools to recover passwords.
- Understand password candidate testing.
- Identify security risks associated with weak and reused passwords.
- Successfully access protected documents using recovered passwords.
- Capture flags embedded within the PDF documents.

---

## 🛠️ Tools Used

| Tool | Description |
|---|---|
| Networkwalks Hash Calculator | Extracts PDF hash data from password-protected documents. |
| Networkwalks Password Cracker | Tests password candidates against extracted hashes to recover passwords. |
| Web Browser | Used to access the online tools. |
| Windows Laptop | Primary lab environment. |

### Tool Links

- [Hash Calculator](https://networkwalks.com/hash-calculator/)
- [Password Cracker](https://networkwalks.com/password-cracker/)
- [Project Lab Instructions](https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/)

---

## ⚙️ Methodology

### Step 1: Download the Password-Protected PDFs

Downloaded the provided password-protected PDF documents from the Networkwalks lab page and saved them locally for analysis.

### Step 2: Extract the PDF Hash

Uploaded each protected PDF to the Networkwalks Hash Calculator.

The tool generated a PDF hash beginning with:

```text
$pdf$
```

The complete hash was copied for the password-recovery process.

### Step 3: Submit the Hash

Opened the Networkwalks Password Cracker and pasted the extracted hash into the designated input field.

### Step 4: Execute the Password-Cracking Process

Started the cracking process and monitored the progress as the tool tested different password candidates.

### Step 5: Recover the Password

The tool identified matching passwords for the protected PDF documents.

### Step 6: Verify Document Access

Entered the recovered passwords into the respective PDF files to confirm successful access.

### Step 7: Capture the Flags

Recorded the flags displayed inside the documents after successfully opening them.

---

## 📊 Password Recovery Results

| PDF File | Recovered Password | Status |
|---|---|---|
| PDF 1 | `password1` | ✅ Recovered |
| PDF 2 | `password1` | ✅ Recovered |
| PDF 3 | `1qaz2wsx` | ✅ Recovered |

All three PDF passwords were successfully recovered.

### Key Observation

PDF 1 and PDF 2 shared the same password, demonstrating the security risk associated with password reuse.

---

## 🔎 Hash Analysis

### PDF 3 Extracted Hash

The following hash was extracted from PDF 3 using the Networkwalks Hash Calculator:

```text
$pdf$4*4*128*-1028*1*16*34eb542eff4e1b0b32d25ce15a9a7281*32*b77872bfc9a24fb2f845066283a8fc1b0021446990b9e4114071a4d9104984c1*32*e7572256e4b552cd57988f5134214b91920d94d7a6bf550ea94a2995c7f2ab02
```

The extracted hash was submitted to the Networkwalks Password Cracker as part of the password-recovery process.

---

## 🚩 Captured Flags

Three flags were recovered during the exercise.

### PDF 2 – Flag 1

```text
nw{networkwalks_flag1_jtr_270521_1}
```

### PDF 2 – Flag 2

```text
nw{networkwalks_persistence_jtr_270521}
```

### PDF 3 – Flag

```text
nw{networkwalks_flag_260821_1}
```

### Flag Summary

| Source | Flag | Status |
|---|---|---|
| PDF 2 | `nw{networkwalks_flag1_jtr_270521_1}` | Captured |
| PDF 2 | `nw{networkwalks_persistence_jtr_270521}` | Captured |
| PDF 3 | `nw{networkwalks_flag_260821_1}` | Captured |

**Total Flags Captured: 3**

---

## 📈 Password Cracker Output

The captured password-cracking output displayed the following information:

| Parameter | Observed Value |
|---|---|
| Attempts / Progress Counter | 91 / 100 |
| Cracking Speed | 9 passwords/second |
| Progress | 91% |
| Recovered Password | `password1` |
| Status | Successful |

The screenshot captured the password-cracking progress and successful password recovery.

> The 91/100 progress reading represents the state displayed in the captured screenshot, not the total attempts across all three PDFs.

---

## 🧠 Technical Concepts Learned

### 1. Password Cracking

Password cracking involves testing possible passwords against password-related verification data to identify a valid password.

### 2. Hashing

Hashing is a one-way cryptographic process that converts input data into a digest. Password recovery tools test candidate passwords and verify whether they match the extracted hash data.

### 3. Encryption

Encryption protects information by transforming readable data into an unreadable form. The appropriate key or password allows authorized users to decrypt the protected information.

### 4. Dictionary Attacks

Dictionary attacks test passwords from collections of commonly used words and password combinations.

Weak and predictable passwords are particularly vulnerable to this approach.

### 5. Password Reuse

Using the same password across multiple files or accounts increases the risk of compromise. If one password is recovered, other resources protected by that password may also become vulnerable.

---

## ⚠️ Security Findings

The exercise highlighted several password-security weaknesses:

- Weak passwords can be recovered using password-cracking tools.
- Password reuse increases the impact of credential compromise.
- Predictable keyboard patterns are poor password choices.
- Password complexity and length contribute to resistance against guessing.
- Password-protected documents should not rely on easily predictable passwords.

---

## 🛡️ Security Recommendations

- Use long, unique, randomly generated passwords.
- Avoid common passwords such as `password1`.
- Avoid predictable keyboard sequences such as `1qaz2wsx`.
- Never reuse passwords across accounts or sensitive documents.
- Use a password manager to generate and store credentials.
- Enable Multi-Factor Authentication (MFA) where available.
- Use appropriate encryption to protect sensitive documents.
- Conduct password-security assessments only with proper authorization.

---

## 📚 Skills Acquired

- PDF hash extraction
- Password recovery techniques
- Hash analysis fundamentals
- Password candidate testing
- Understanding dictionary-based attacks
- Encryption versus hashing
- Password security assessment
- Identification of weak passwords
- Recognition of password reuse risks
- Cybersecurity lab documentation

---

## 📝 Conclusion

This practical exercise provided hands-on experience with password cracking using the Networkwalks Hash Calculator and Password Cracker.

I successfully recovered passwords from three protected PDF documents, verified access to the files, and captured three laboratory flags.

The exercise demonstrated how weak, predictable and reused passwords can compromise the security of protected information.

It reinforced the importance of strong password practices, unique credentials and proper security controls when protecting sensitive files.

---

## ⚖️ Disclaimer

This project was performed within an authorized cybersecurity training environment for educational purposes.

Password-cracking techniques should only be used against systems, files or accounts for which explicit authorization has been granted.

---

**Program:** Networkwalks Cybersecurity & Ethical Hacking Internship  
**Week:** 3  
**Project Module:** 2  
**Project:** Password Cracking with Networkwalks Tools  
**Status:** Completed ✅
