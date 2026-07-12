# SQL Injection (SQLi) Payloads

<p align="left">
  <img src="https://img.shields.io/github/license/Pablo-RJ/sql-injection-payloads?style=for-the-badge&color=blue" alt="License" />
  <img src="https://img.shields.io/github/repo-size/Pablo-RJ/sql-injection-payloads?style=for-the-badge&color=green" alt="Repository Size" />
  <img src="https://img.shields.io/github/languages/code-size/Pablo-RJ/sql-injection-payloads?style=for-the-badge&color=orange" alt="Code Size" />
  <img src="https://img.shields.io/github/last-commit/Pablo-RJ/sql-injection-payloads?style=for-the-badge" alt="Last Commit" />
</p>

A curated, comprehensive compilation of over **900+ SQL Injection (SQLi)** payloads designed for security research, penetration testing, Web Application Firewall (WAF) evasion testing, and vulnerability assessment.

> [!WARNING]
> **Disclaimer:** This repository and the payloads contained herein are intended solely for educational, research, and authorized penetration testing purposes. Using these payloads against systems without explicit, written consent from the owner is illegal and punishable by law. The author assumes no responsibility for any misuse or damage caused by these materials.

---

## 📂 Repository Structure

* `payloads.txt`: The main wordlist containing various SQL injection payloads categorized by type (Auth bypass, Union based, Time-based blind, Error-based, etc.).
* `README.md`: Project documentation and guidelines.
* `LICENSE`: MIT License.

## 📊 Payload Categories Included

The [payloads.txt](payloads.txt) file contains standard and advanced techniques, including:
* **Authentication Bypass:** Classic `' OR '1'='1` variants and comment-based bypasses.
* **UNION-Based:** Payloads for schema and data extraction via union queries.
* **Error-Based:** Database-specific error trigger functions (MySQL, PostgreSQL, MS SQL, Oracle).
* **Time-Based Blind:** Sleep and benchmark payloads to detect blind vulnerabilities.
* **Inline Comments & Obfuscation:** Bypass techniques using spaces, hex encoding, and SQL-specific comment markers (`/**/`, `/*!50000...*/`).

## 🚀 How to Use

These payloads can be integrated into popular security auditing tools:
* **OWASP ZAP** or **Burp Suite** (using the Fuzzer / Intruder tool).
* **SQLMap** (for custom dictionary attacks).
* Custom Python/Bash automation scripts to test WAF rule robustness.

## 🤝 Contributing

Contributions are welcome! If you have new payloads, bypass techniques, or improvements:
1. Fork the repository.
2. Create a branch (`git checkout -b feature/new-payloads`).
3. Add your payloads to `payloads.txt`.
4. Commit your changes and open a Pull Request.

## 📄 License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

