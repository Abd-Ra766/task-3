# Task 3 - Vulnerability Assessment using Nessus Essentials

## 📌 Objective:
Perform a basic vulnerability scan on a personal computer using a free vulnerability scanner to identify security issues and learn how to analyze them.

## 🛠 Tools Used:
- **Nessus Essentials** by Tenable (free version)
- Windows 10 PC
- Web browser for Nessus interface

---

## 🧪 Steps Performed:

1. **Installed Nessus Essentials** from the [Tenable official site](https://www.tenable.com/products/nessus/nessus-essentials).
2. Registered for an activation code (free) and activated Nessus.
3. Set the scan target as `localhost` (my own computer).
4. Created and ran a **Basic Network Scan**.
5. Allowed the scan to complete (approx. 45 mins).
6. Downloaded the vulnerability scan report as PDF.
7. Identified critical vulnerabilities.
8. Took screenshots of the dashboard showing issues.
9. Researched and documented fixes for major vulnerabilities.

---

## 📊 Report Summary:

- **Critical Vulnerabilities:** 3
  - Outdated Windows SMBv1 Protocol
  - Remote Desktop Protocol (RDP) exposed without Network Level Authentication
  - Adobe Flash Player End-of-Life still present
- **High Vulnerabilities:** 5
- **Medium/Low Issues:** 10+

---

## 🔧 Suggested Fixes:

1. **Disable SMBv1** via Windows Features.
2. **Enable NLA** for RDP via System Properties → Remote Settings.
3. **Uninstall Adobe Flash Player** completely.

---

## 🖼 Screenshots:
- Nessus scan dashboard
- Critical issue highlight
- Remediation tips

---

## 📎 Files Included:
- `scan-report.pdf`
- `screenshots/` folder (3 images)
- `README.md` (this file)

---

## 🔗 Submission Link:
[Submit using this Google Form](https://forms.gle/8Gm83s53KbyXs3Ne9)
