# NETWORKWALKS CYBERSECURITY & ETHICAL HACKING INTERNSHIP

## WEEK 3 – PROJECT MODULE 2
# PASSWORD CRACKING WITH NETWORKWALKS TOOLS

**Project Category:** Cybersecurity and Ethical Hacking  
**Project Module:** 2  
**Week:** 3  
**Platform:** Networkwalks Academy  
**Tools Used:** Networkwalks Hash Calculator and Networkwalks Password Cracker  
**Operating Environment:** Windows Laptop / Web Browser  

---

# 1. INTRODUCTION

Password security is one of the fundamental components of information security. Passwords are commonly used to protect sensitive information, restrict unauthorized access and authenticate users across computer systems and applications.

However, weak or predictable passwords can expose individuals and organizations to security threats. Attackers may use password-cracking techniques to recover passwords from stored password hashes or encrypted files.

Password cracking is the process of attempting to recover an original password by testing possible password combinations against a stored hash or other password-verification data.

During this practical exercise, I explored password cracking using two online cybersecurity tools developed by Networkwalks:

1. **Networkwalks Hash Calculator:** Used to extract password-related hash data from password-protected PDF documents.
2. **Networkwalks Password Cracker:** Used to test possible passwords against the extracted PDF hashes until a matching password was identified.

The exercise involved three password-protected PDF documents. I extracted their hashes, submitted the hashes to the password-cracking tool, recovered their passwords and accessed the protected documents.

The practical exercise also involved identifying and recording flags embedded in the documents as evidence of successful completion.

---

# 2. PROJECT OBJECTIVES

The primary objectives of this practical exercise were to:

1. Understand the fundamentals of password cracking.
2. Understand the difference between encryption and hashing.
3. Learn how to extract PDF password hashes using the Networkwalks Hash Calculator.
4. Understand how password-cracking tools test potential passwords against extracted hashes.
5. Recover passwords from three password-protected PDF documents.
6. Successfully access the protected PDF documents using their recovered passwords.
7. Identify and capture the flags embedded in the documents.
8. Understand the security risks associated with weak and predictable passwords.
9. Develop practical knowledge of password security assessment techniques.

---

# 3. TOOLS AND TECHNOLOGIES USED

The following tools and technologies were used during the exercise.

### 3.1 Networkwalks Hash Calculator

The Networkwalks Hash Calculator is a browser-based tool used in this exercise to extract password hash information from protected PDF documents.

After uploading an encrypted PDF document, the tool generates a hash beginning with `$pdf$`.

This hash contains the information required by the compatible password-cracking tool to test possible passwords.

Website: https://networkwalks.com/hash-calculator/

### 3.2 Networkwalks Password Cracker

The Networkwalks Password Cracker is an online password-recovery tool used to test potential passwords against extracted PDF hashes.

The tool attempts different password candidates until it identifies a password that successfully matches the extracted hash.

During this exercise, the tool displayed the attempted passwords, attack progress, password-testing speed and successful password matches.

Website: https://networkwalks.com/password-cracker/

### 3.3 Web Browser

A web browser was used to access both Networkwalks tools. No additional software installation was required for the password extraction and cracking process.

### 3.4 Password-Protected PDF Documents

Three encrypted PDF documents were used as the targets of the authorized laboratory exercise:

- My Locked PDF 1
- My Locked PDF 2
- PDF 3

---

# 4. METHODOLOGY AND PRACTICAL IMPLEMENTATION

The practical exercise was performed in several stages, beginning with downloading the protected documents and ending with successfully recovering their passwords.

## STEP 1: Downloading the Password-Protected PDF Documents

I accessed the Networkwalks Week 3 project task page and downloaded the password-protected PDF documents required for the exercise.

The documents were saved locally on my laptop for further analysis.

Project instructions:
https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/

**Observation:**

The downloaded documents were password-protected and required valid passwords before their contents could be accessed.

## STEP 2: Accessing the Networkwalks Hash Calculator

I opened the Networkwalks Hash Calculator through my web browser.

The tool provides an interface for uploading protected PDF documents and extracting their corresponding password hash data.

Website:
https://networkwalks.com/hash-calculator/

## STEP 3: Extracting the PDF Password Hashes

I uploaded the password-protected PDF documents individually into the Hash Calculator.

The tool processed the uploaded files and generated hash values beginning with `$pdf$`.

These hash values were required for the subsequent password-cracking process.

**Technical observation:**

The extracted PDF hash provides the password-cracking tool with the data required to test possible passwords against the document's password protection.

## STEP 4: Copying the Extracted Hash

After the extraction process, I copied the complete hash value generated by the Hash Calculator.

It was important to copy the entire hash without omitting any characters because an incomplete or incorrectly copied hash could prevent the cracking tool from processing it successfully.

For PDF 3, the extracted hash was:

```text
$pdf$4*4*128*-1028*1*16*34eb542eff4e1b0b32d25ce15a9a7281*32*b77872bfc9a24fb2f845066283a8fc1b0021446990b9e4114071a4d9104984c1*32*e7572256e4b552cd57988f5134214b91920d94d7a6bf550ea94a2995c7f2ab02
```

This hash was subsequently submitted to the Networkwalks Password Cracker.

## STEP 5: Accessing the Networkwalks Password Cracker

I opened the Networkwalks Password Cracker using the web browser.

The extracted PDF hash was pasted into the appropriate input field.

I initiated the password-cracking process and allowed the tool to test possible password combinations.

Website:
https://networkwalks.com/password-cracker/

## STEP 6: Executing the Password-Cracking Process

After submitting the hash, the password-cracking tool began testing different password candidates.

The interface displayed the attempted passwords and indicated whether each attempt was successful.

During one of the cracking sessions, the following information was displayed:

- Attempts recorded: 91 out of 100.
- Password-testing speed: 9 passwords per second.
- Displayed progress: 91%.
- Final result: Successful password recovery.
- Recovered password: `password1`.

The tool eventually displayed a successful match.

**Technical observation:**

The exercise demonstrated how password candidates can be tested systematically against an extracted PDF hash.

The successful recovery of a password showed that the document was protected using a password that could be identified within the tool's tested candidates.

## STEP 7: Recovering the Passwords

The password-cracking process was performed on all three PDF documents.

The recovered passwords were:

| PDF Document | Recovered Password |
|---|---|
| My Locked PDF 1 | password1 |
| My Locked PDF 2 | password1 |
| PDF 3 | 1qaz2wsx |

An important observation was that the first and second PDF documents shared the same password, while the third document used a different password.

This demonstrated the risk associated with password reuse and predictable password choices.

## STEP 8: Opening the Protected PDF Documents

After recovering the passwords, I opened the respective PDF documents and entered the recovered passwords.

The documents became accessible after the correct passwords were entered.

This confirmed that the recovered passwords matched the password protection applied to the documents.

The documents also contained flags that were recorded as additional evidence of successful laboratory completion.

---

# 5. RESULTS AND FINDINGS

The practical exercise was successfully completed, with passwords recovered from all three protected PDF documents.

### 5.1 Password Recovery Results

| S/N | Target Document | Recovered Password | Status |
|---|---|---|---|
| 1 | PDF 1 | password1 | Successful |
| 2 | PDF 2 | password1 | Successful |
| 3 | PDF 3 | 1qaz2wsx | Successful |

**Overall Result:** All three PDF passwords were successfully recovered.

### 5.2 Password Cracker Performance Observation

One of the screenshots captured during the exercise showed the following performance information:

| Parameter | Recorded Value |
|---|---|
| Attempts displayed | 91/100 |
| Cracking speed | 9 passwords per second |
| Progress | 91% |
| Recovery status | Successful |
| Recovered password | password1 |

The screenshot demonstrated the password-testing process and the successful identification of the password.

Note: The 91/100 progress reading is the displayed state captured in the screenshot, not a confirmed total number of attempts required across all three documents.

---

# 6. FLAG CAPTURE AND VERIFICATION

As part of the practical exercise, the password-protected documents contained flags that were displayed after successful password recovery and document access.

These flags served as additional evidence of progress and successful completion of the laboratory activities.

### 6.1 PDF 2 – First Captured Flag

After recovering the password and accessing the document, the following flag was displayed:

```text
nw{networkwalks_flag1_jtr_270521_1}
```

### 6.2 PDF 2 – Second Captured Flag

Another flag displayed during the PDF 2 exercise was:

```text
nw{networkwalks_persistence_jtr_270521}
```

This flag reinforced the importance of patience and persistence when performing password-cracking exercises.

### 6.3 PDF 3 – Captured Flag

After recovering the password for PDF 3 and accessing the document, the following flag was displayed:

```text
nw{networkwalks_flag_260821_1}
```

### 6.4 Flag Summary

| S/N | PDF Document | Captured Flag | Status |
|---|---|---|---|
| 1 | PDF 2 | nw{networkwalks_flag1_jtr_270521_1} | Captured |
| 2 | PDF 2 | nw{networkwalks_persistence_jtr_270521} | Captured |
| 3 | PDF 3 | nw{networkwalks_flag_260821_1} | Captured |

**Total Flags Captured: 3**

---

# 7. TECHNICAL CONCEPTS LEARNED

The practical exercise provided an opportunity to understand several important cybersecurity concepts.

## 7.1 Password Cracking

Password cracking involves attempting to recover a password by testing possible candidates against password-related verification data.

Security professionals use password-cracking techniques during authorized security assessments to identify weak passwords and evaluate authentication security.

Common password-cracking approaches include:

- Dictionary attacks.
- Brute-force attacks.
- Hybrid attacks.
- Rule-based attacks.

The Networkwalks exercise demonstrated password recovery through the testing of password candidates.

## 7.2 Hashing

Hashing is a one-way cryptographic process that converts input data into a fixed-length digest.

Unlike encryption, hashing is not designed to be reversed using a decryption key.

In password security, systems commonly store password hashes instead of storing passwords directly.

During this exercise, the Hash Calculator extracted a PDF-compatible hash representation that could be processed by the Password Cracker.

## 7.3 Encryption

Encryption is a process of converting readable information (plaintext) into an unreadable form (ciphertext) using an encryption algorithm and key.

Unlike hashing, encryption is designed to be reversible when the correct decryption key or password is available.

The PDF documents used in this exercise were password-protected, and the recovered passwords allowed access to their contents.

## 7.4 Dictionary Attacks

A dictionary attack is a password-cracking technique that uses a predefined collection of possible passwords.

Instead of testing every possible character combination, the tool tests words and password candidates from a wordlist.

Common passwords such as `password1`, `123456` and other predictable combinations are particularly vulnerable to dictionary-based attacks.

The exercise demonstrated why users should avoid predictable passwords.

## 7.5 Password Reuse

Password reuse occurs when the same password is used across multiple accounts, applications or protected documents.

During the exercise, PDF 1 and PDF 2 were found to use the same password.

This highlighted an important security weakness: if one password is compromised, other resources protected by the same password may also become vulnerable.

---

# 8. SECURITY OBSERVATIONS

Several important security observations were made during the exercise.

**1. Weak Passwords Are Vulnerable**

The recovered passwords demonstrated how predictable password choices can expose protected documents to unauthorized access.

**2. Password Reuse Creates Additional Risk**

PDF 1 and PDF 2 shared the same password. Reusing passwords increases the potential impact of a successful password compromise.

**3. Password Complexity Matters**

Passwords should contain sufficient length and unpredictability. Combining uppercase letters, lowercase letters, numbers and special characters can improve resistance to guessing attacks.

**4. Wordlists Can Be Effective**

Dictionary-based password testing can identify passwords that appear in the tested wordlist.

**5. Password Recovery Requires Appropriate Tools**

The exercise demonstrated how hash-extraction and password-cracking tools can work together during an authorized security assessment.

---

# 9. SECURITY RECOMMENDATIONS

Based on the observations made during the exercise, the following security recommendations are proposed:

1. **Use Strong Passwords:** Create long, unique and unpredictable passwords instead of relying on common words or simple combinations.

2. **Avoid Password Reuse:** Use different passwords for different accounts and protected documents.

3. **Use a Password Manager:** Password managers help generate and securely store complex passwords.

4. **Enable Multi-Factor Authentication:** Where available, MFA provides an additional layer of protection beyond passwords.

5. **Protect Sensitive Documents:** Apply appropriate encryption and access-control mechanisms to confidential PDF documents.

6. **Perform Regular Security Assessments:** Organizations should periodically assess password security to identify weak credentials.

7. **Avoid Common Password Patterns:** Passwords such as `password1`, `12345678` and predictable keyboard sequences should be avoided.

8. **Secure Password Hash Storage:** Applications should use established password-hashing algorithms designed for password storage, such as Argon2id, bcrypt or scrypt, with appropriate configuration and unique salts.

9. **Conduct Authorized Testing Only:** Password-cracking tools should only be used on files, systems and accounts for which explicit authorization has been obtained.

---

# 10. CHALLENGES ENCOUNTERED

The practical exercise required careful execution of each stage to achieve successful password recovery.

Some important considerations during the exercise included:

- Ensuring that the complete PDF hash was copied correctly.
- Submitting the extracted hash into the appropriate password-cracking interface.
- Allowing the password-cracking process to complete.
- Monitoring the attempted password candidates and cracking progress.
- Ensuring that the recovered password was entered correctly when opening each PDF document.
- Recording the flags displayed after accessing the documents.

The exercise reinforced the importance of accuracy, patience and attention to detail when performing cybersecurity laboratory activities.

---

# 11. SKILLS AND KNOWLEDGE ACQUIRED

At the end of the exercise, I gained practical exposure to the following areas:

- Understanding password-cracking fundamentals.
- Extracting PDF password hashes.
- Using browser-based cybersecurity tools.
- Performing password recovery through hash-based testing.
- Understanding dictionary-based password attacks.
- Identifying weak and predictable passwords.
- Understanding the differences between hashing and encryption.
- Recognizing password reuse vulnerabilities.
- Verifying recovered passwords by opening protected documents.
- Capturing and documenting laboratory flags.
- Applying password-security best practices.

---

# 12. CONCLUSION

The Networkwalks Week 3 Project Module 2 exercise provided valuable practical exposure to password cracking and document security assessment.

Through the use of the Networkwalks Hash Calculator and Password Cracker, I successfully extracted password hashes from protected PDF documents and recovered the passwords required to access them.

A total of three PDF documents were tested, and all three passwords were successfully recovered. PDF 1 and PDF 2 shared the password `password1`, while PDF 3 used `1qaz2wsx`.

I also successfully captured three laboratory flags from PDF 2 and PDF 3, providing additional evidence of successful completion.

One of the major lessons from this exercise was that weak and predictable passwords can significantly reduce the security of protected documents. The exercise also demonstrated the risks associated with password reuse.

Overall, this project strengthened my understanding of password security, hashing, encryption, dictionary-based attacks and the practical use of password-cracking tools during authorized cybersecurity assessments.

It also reinforced the importance of using strong, unique passwords and implementing appropriate security controls to protect sensitive information.

**PROJECT STATUS: SUCCESSFULLY COMPLETED**

---


**END OF REPORT**

**NETWORKWALKS CYBERSECURITY & ETHICAL HACKING INTERNSHIP – WEEK 3**
