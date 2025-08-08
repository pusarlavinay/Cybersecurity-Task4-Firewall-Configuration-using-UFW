# 🛡️ Task 4: Firewall Configuration using UFW

## 🎯 Objective
To understand basic Linux firewall configuration using **UFW (Uncomplicated Firewall)**. This includes allowing trusted services and blocking vulnerable ports.

---

## 🧰 Tools & Environment
- OS: Kali Linux (or any Debian-based Linux)
- Firewall Tool: UFW (Uncomplicated Firewall)
- Terminal access with root privileges

---

## 🔧 Steps Performed

1. Installed UFW using `sudo apt install ufw`.
2. Enabled the firewall with `sudo ufw enable`.
3. Allowed SSH access on port 22 using `sudo ufw allow 22`.
4. Blocked Telnet (port 23) using `sudo ufw deny 23`.
5. Verified all active rules using `sudo ufw status numbered`.
6. (Optional) Tested blocking by running `telnet localhost 23`.
7. Removed Telnet block rule with `sudo ufw delete deny 23` (cleanup).

---

## 🧾 Files Included
- `commands-used.txt`: Terminal commands used throughout the task.
- `screenshots/`: Captures of each step for validation.
- `README.md`: Documentation of the entire task.

---

## ✅ Final Result
Firewall successfully configured using UFW:
- **SSH (22)** → Allowed ✅  
- **Telnet (23)** → Blocked ❌  
Firewall rules verified and working as expected.

---

## 🙋 Submitted By
**Name**: Pusarla Vinay  
**Task**: Task 4 - UFW Firewall Setup  
**Platform**: Kali Linux  
