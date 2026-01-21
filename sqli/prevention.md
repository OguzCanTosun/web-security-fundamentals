# SQL Injection – Prevention

## 🔹 Secure Coding Practices
- Use prepared statements
- Input validation
- Least privilege DB users

---

## 🔹 Example (Safe)
```sql
SELECT * FROM users WHERE username = ?;
