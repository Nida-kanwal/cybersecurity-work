# Cybersecurity Internship Project

## 📌 Overview
This repository contains all tasks completed during my **Cybersecurity Internship**, including vulnerability testing, fixing security flaws, and applying best practices to secure a Node.js web application.

---

## 🛠 Tools & Technologies
- **OWASP ZAP** – Vulnerability scanning
- **Node.js + Express.js** – Web application backend
- **Kali Linux** – Security testing environment
- **Git & GitHub** – Version control

---

## 📅 Week-wise Progress

### Week 1 – Vulnerability Testing
- Set up a mock vulnerable web app (OWASP Juice Shop).
- Performed **XSS** and **SQL Injection** attacks.
- Generated OWASP ZAP report showing:
  - 1 High (SQL Injection)
  - 5 Medium (Missing CSP, Session ID in URL, etc.)
  - 4 Low & 3 Informational alerts.

### Week 2 – Fixing Vulnerabilities
- Added **input validation** to prevent injection attacks.
- Implemented **password hashing** using bcrypt.
- Integrated **JWT authentication** for secure logins.
- Applied **Helmet.js** for securing HTTP headers.

### Week 3 – Final Testing & Reporting
- Performed **penetration testing** and verified fixes.
- Set up **logging** with Winston.
- Prepared **final project report** and recorded demo video.

---

## 📂 Folder Structure
