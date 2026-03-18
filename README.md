
## 📁 Repository Structure
 
```
📦 cybersecurity-lab-module1
 ┣ 📄 README.md               ← You are here
 ┗ 📄 Rapport_Lab1.pdf        ← Full lab report (FR)
```
 
---
 
## 🔬 Lab Summary
 
### Part 1 — Password Security
Created 3 strong passwords following best practices:
- Minimum 12 characters
- Mix of uppercase, lowercase, digits and special characters
 
### Part 2 — Network Traffic Capture
- Captured **63,542 packets** over ~2 minutes of browsing
- Visited: `fr.wikipedia.org`, `www.bing.com`, `edge.microsoft.com`
- DNS domain observed: `upload.wikimedia.org`
 
### Part 3 — Packet Analysis
 
| Filter | Result |
|--------|--------|
| `dns` | 320 packets — domain name resolutions visible |
| `http` | **0 packets** — all modern sites use HTTPS |
| `tls` | 18,720 packets — encrypted HTTPS traffic |
 
---
 
## ❓ Key Questions & Answers
 
**Why is encryption important?**  
Encryption transforms data into unreadable content for any third party intercepting packets. Without it, passwords, personal data and financial information travel in plain text across the network.
 
**What can attackers obtain from unencrypted traffic?**  
Login credentials, visited URLs, form data, session cookies, and banking details.
 
---
 
## 📖 Report
 
> 📄 The full lab report (in French) is available here: [`rapport_lab1.pdf`](./Rapport_Lab1.pdf)
 
---
 
## 🔑 Security Lessons Learned
 
- **Weak passwords** are easily cracked by dictionary and brute-force attacks
- **Network traffic is capturable** by anyone on the same network
- **HTTP exposes data** in plain text — never submit sensitive info on HTTP sites
- **HTTPS/TLS protects** confidentiality, integrity, and authenticity of communications
