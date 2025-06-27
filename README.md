# Internship-By-Elevate-Labs
# Task 4 - Linux Firewall Configuration using UFW

## 🔍 Objective
To configure and test firewall rules on a Linux system using UFW, demonstrating basic network traffic filtering skills.

---

## 🧰 Tools Used
- Kali Linux VM
- UFW (Uncomplicated Firewall)
- Nmap (for port testing)

---

## 🧑‍💻 Steps Performed

1. Checked firewall status using `sudo ufw status verbose`
2. Enabled UFW with `sudo ufw enable`
3. Blocked port 23 (Telnet) with `sudo ufw deny 23`
4. Tested the block using `nmap -p 23 localhost`
5. Allowed port 22 (SSH) with `sudo ufw allow 22`
6. Removed the test rule using `sudo ufw delete <rule_number>`
7. Verified all rules using `sudo ufw status numbered`

---

## 🖼 Screenshots
- UFW status before enabling
- Rule blocking port 23
- Nmap test showing port 23 is closed
- SSH port 22 allowed
- Final rules shown via `ufw status numbered`

---

## ✅ Outcome
Successfully configured a firewall to allow and block specific traffic using UFW, reinforcing practical Linux network security concepts.
