# 🕵️‍♀️ SQL Murder Mystery — Solved Case Report

## 📘 Project Overview

In this capstone project, I took on the role of a **Lead Data Analyst** investigating the mysterious death of the CEO of **TechNova Inc.**  
My objective was to utilise SQL to analyse multiple datasets — including **keycard logs**, **phone records**, **alibis**, and **crime-scene evidence** — to determine:

- **Who committed the crime**
- **Where it occurred**
- **When it happened**
- **How it was carried out**

This project allowed me to apply a wide range of SQL concepts such as:

- Joins  
- Subqueries  
- Filters  
- Aggregations  
- Common Table Expressions (CTEs)  
- Logical reasoning & problem-solving  

At the end of the analysis, I compiled:

- All **SQL queries** used  
- A final **“Case Solved” conclusion** identifying the culprit  

---

## 🕵️ Investigation Steps & Findings

### 🔎 1. Who entered the CEO’s Office close to the time of the murder?

### 🔎 2. Who claimed to be somewhere else but was not?

📸 **Screenshot:**  
`who_entered_ceo_office_&_false_alibi.png`

#### ➡️ Findings:

- **David Kumar** entered the CEO Office between **20:50–21:00**.  
- He gave a **false alibi**, claiming he was in the Server Room, while keycard logs proved otherwise.

---

### 📞 3. Who made or received calls around 20:50–21:00?

### 🧪 4. What evidence was found at the crime scene?

📸 **Screenshot:**  
`calls_&_evidence_at_scene.png`

#### ➡️ Findings:

- A **suspicious call at 20:55** was linked to **David Kumar**.  
- Evidence found at the CEO Office included:
  - Fingerprints on the desk  
  - A keycard swipe mismatch  

---

## 🧩 5. Identify the Killer — Final Combined Analysis

To identify the killer, I combined all key clues:

- Presence at the CEO’s Office during the crime window  
- Verification of false alibi  
- Call activity during the incident  
- Physical evidence found at the scene  

📸 **Screenshots:**  
`combined_analysis_ctes_part_1.png`  
`combined_analysis_ctes_part_2.png`

---

## 🏁 **Final Conclusion — Case Solved**

### 🔪 **Killer Identified: David Kumar**

---

## 🧠 How I Reached the Conclusion

- The suspect was **inside the CEO Office** during the murder window (20:50–21:00).  
- He provided a **false alibi**, claiming he was in the Server Room.  
- His **phone call activity** coincided with the time of the murder.  
- **Physical evidence** (fingerprints + keycard mismatch) matched his presence.  

By combining all these clues, I conclusively identified **David Kumar** as the killer.

---




