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

---

## 5️⃣ `sqli/exploitation.md`

```md
# SQL Injection – Exploitation

## 🔹 Basic Payload
' OR '1'='1

---

## 🔹 Exploitation Flow
1. Identify input field
2. Test for injection
3. Extract data

---

## 🔹 Impact
- Unauthorized access
- Sensitive data exposure
