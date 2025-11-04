# Day 2 – 21 Days SQL Challenge (By Indian Data Club)

This is my **Day 2** submission for the [21 Days SQL Challenge](https://www.linkedin.com/company/indiandataclub/) organized by **Indian Data Club** and **@DPDZero**.  
**Tag:** #SQLWithIDC  

---

### 🧠 Topics Covered
`WHERE` clause, comparison operators, basic filtering

---

### 🧩 Task Overview
**Question:**  
Find all patients admitted to `'Surgery'` service with a satisfaction score below **70**, showing their `patient_id`, `name`, `age`, and `satisfaction_score`.

---

### 🧮 Query Used
```sql
SELECT
    patient_id,
    name,
    age,
    satisfaction AS satisfaction_score
FROM patients
WHERE service = 'Surgery'
  AND satisfaction < 70;
