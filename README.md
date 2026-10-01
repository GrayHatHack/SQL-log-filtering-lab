# SQL Security Log Filtering Lab

## 📌 Objective
To practice writing SQL queries and applying filters (such as `WHERE`, `AND`, `OR`, `LIKE`) to analyze security logs, track user login activities, and identify potential unauthorized access attempts in a database.

---

## 🛠️ Tools & Technologies Used
* **Database Language:** SQL
* **Key Concepts:** Filtering data, Conditional operators (`WHERE`, `LIKE`, `IN`), Log analysis

---

## 📋 Sample Scenarios & Queries

1. **Filtering Failed Login Attempts:**
   * Used conditional filters to query log entries where the login status returned an error or failure code.
   ```sql
   SELECT * FROM log_files WHERE login_status = 'FAILED';

---
## 📸 Screenshots
![SQL Query Output](Screenshot%202026-10-01%20054825.png)

🚀 Key Takeaway
Learned how security analysts use SQL queries to quickly sift through thousands of log entries to pinpoint specific security anomalies and investigate incidents.
