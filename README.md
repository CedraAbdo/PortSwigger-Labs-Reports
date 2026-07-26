# 📚 PortSwigger Labs - Solution Reports

> This repository is dedicated to documenting solutions for the PortSwigger Web Security Academy labs, as part of the Network Security course curriculum.

---

## 🎯 Objectives of this Repository

This repository aims to achieve the following:

1. **Deep Understanding of Vulnerability Types**: Distinguish between vulnerabilities (SQLi, XSS, CSRF, SSRF) and understand how each one works.
2. **Mastering Penetration Testing Tools**: Gain hands-on experience using (Burp Suite) and its extensions to intercept and modify HTTP requests.
3. **Documenting the Methodology**: Write down attack steps in an organized manner, outlining the logical thought process of an ethical hacker.
4. **Bridging Theory and Practice**: Translate academic knowledge (e.g., protocol explanations) into real-world practical application.
5. **Developing Report-Writing Skills**: Create professional reports similar to those written by security analysts in companies, including analysis and conclusions.

---

## 📂 Vulnerability Categories

This repository covers the following main categories of security vulnerabilities (more will be added later as the course progresses):

| Category | Brief Description | Dedicated Folder |
|----------|-------------------|-------------------|
| **SQL Injection (SQLi)** | A vulnerability that allows an attacker to alter database queries, leading to the display or modification of sensitive data, or bypassing login credentials. Considered one of the most critical vulnerabilities. | [`/SQL-Injection`](./SQL-Injection) |
| **Cross-Site Scripting (XSS)** | A vulnerability that allows injecting malicious scripts (usually JavaScript) into web pages. These scripts execute in the victim's browser to steal cookies or perform actions on their behalf. | [`/XSS`](./XSS) |
| **Cross-Site Request Forgery (CSRF)** | A vulnerability that tricks an authenticated user (logged-in) into performing an unwanted action (like changing their password) without their knowledge, simply by clicking a malicious link. | [`/CSRF`](./CSRF) |
| **Server-Side Request Forgery (SSRF)** | A vulnerability that exploits the server to send HTTP requests to internal addresses (Internal Networks) that are not directly accessible to the attacker, potentially exposing the internal network structure. | [`/SSRF`](./SSRF) |
| **Directory Traversal (Path Traversal)** | A vulnerability that allows an attacker to access files and folders outside the web root directory, potentially leading to the reading of sensitive system files (e.g., `/etc/passwd`). | [`/Directory-Traversal`](./Directory-Traversal) |
| **Authentication Vulnerabilities** | A group of vulnerabilities related to login and authentication mechanisms, such as weak password policies, "Remember Me" flaws, or authentication bypasses. | [`/Authentication`](./Authentication) |
| **Miscellaneous (Other)** | Any new category not mentioned above will be added here, such as (NoSQL Injection) or (XXE). | [`/Other`](./Other) |

---

## 🗓️ Achievement Log

| Lab Number | Category | Date | Status |
|------------|----------|------|--------|
| Lab-01 | ...... | ..../../.... | ⬜ Not started |
| Lab-02 | ...... | ..../../.... | ⬜ Not started |
| Lab-03 | ...... | ..../../.... | ⬜ Not started |
| ... | ... | ... | ... |

*(This table will be updated with each solved lab)*

---

## 🛠️ Essential Tools Used

- **Burp Suite (Community/Professional)**: The primary tool for intercepting and modifying requests (Proxy, Repeater, Intruder).
- **Browser (Chrome/Firefox)**: Along with the **FoxyProxy** extension to route traffic to Burp.
- **Turbo Intruder** (Optional): To speed up brute-force attacks.
- **Command Line (Linux)**: To use additional tools or run helper scripts.

---

## 📝 General Notes

- All reports are written in **Markdown** (.md) format for easy readability on GitHub.
- **Screenshots** will be attached for each important step inside the `screenshots/` folder within each category.
- Ethical commitment: These solutions are applied exclusively to the authorized PortSwigger labs and not to any live systems without permission.
