# Task 4: Password Security & Authentication Analysis

## Overview
This repository contains the work completed for Task 4 of the cybersecurity internship.
The objective of this task was to analyze password storage mechanisms, identify different
hash types, perform password cracking attacks, and study defensive authentication
mechanisms.

All experiments were conducted on self-generated hashes for educational purposes.

---

## Tools Used
- John the Ripper
- Hashcat
- Kali Linux
- rockyou.txt wordlist

---

## Objectives
- Understand password storage (hashing vs encryption)
- Identify common hash types (MD5, SHA-1, SHA-256)
- Generate password hashes
- Perform dictionary and brute-force attacks
- Analyze weak password vulnerabilities
- Study Multi-Factor Authentication (MFA)
- Recommend strong authentication practices

---

## Work Performed

### 1. Password Hash Generation
MD5, SHA-1, and SHA-256 hashes were generated using Linux command-line utilities.

### 2. Hash Identification
Hash types were identified based on hash length and structure.

### 3. Password Cracking
Dictionary attacks were performed using John the Ripper and the rockyou.txt wordlist.

Results:
- MD5 hash cracked successfully
- SHA-1 hash cracked successfully
- SHA-256 hash cracked due to weak password selection

This demonstrated that even strong hashing algorithms cannot protect accounts if weak
passwords are used.

### 4. Security Analysis
The task highlighted how weak passwords are vulnerable regardless of the hashing algorithm
used and emphasized the importance of strong password policies and MFA.

---

## Repository Structure
Task-4-Password-Security-Authentication/
─ hashes.txt
─ sha1.txt
- sha256.txt
── commands-used.txt
── README.md


---

## Key Learnings
- Weak passwords can be cracked quickly using dictionary attacks
- MD5 and SHA-1 are insecure for password storage
- Strong hashing algorithms alone are not sufficient
- Password strength and MFA are critical for security

---

## Disclaimer
This project was performed strictly for educational and ethical purposes as part of a
cybersecurity internship. No real user data was used.
