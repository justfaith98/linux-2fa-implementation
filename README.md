# linux-2fa-implementation
Linux system hardening project implementing Google Authenticator 2FA for console, SSH, and sudo access.

# Linux Two-Factor Authentication Implementation

## 📌 Overview
This project demonstrates the implementation of Two-Factor Authentication (2FA) on a Linux (Ubuntu) server using Google Authenticator.

The objective was to enhance system security by enforcing multi-factor authentication for:
- Console login
- SSH login
- Public key authentication
- Sudo privilege escalation

---

## 🛠 Technologies Used
- Ubuntu Server
- PAM (Pluggable Authentication Modules)
- OpenSSH
- Google Authenticator
- SSH Key Authentication

---

## 🔧 Implementation Steps

### 1️⃣ Install & Configure Google Authenticator
```bash
google-authenticator
