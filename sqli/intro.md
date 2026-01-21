# SQL Injection (SQLi) – Introduction

## 🔹 What is SQL Injection?
SQL Injection occurs when user input is improperly handled and directly included in SQL queries.

---

## 🔹 Why It Is Dangerous
- Data leakage
- Authentication bypass
- Full database compromise

---

## 🔹 Example Vulnerable Query
```sql
SELECT * FROM users WHERE username = '$username';
