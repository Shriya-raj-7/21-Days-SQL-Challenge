# 🕵️‍♀️ SQL Murder Mystery — Solved Case Report

Welcome to my SQL Murder Mystery mini-project!
I solved a fictional murder case using SQL by analysing keycard logs, alibis, phone calls, and evidence found at the crime scene.
This README includes the description of each investigation step along with screenshots of results. 🔍✨

🔎 1. Who entered the CEO’s Office close to the time of the murder?
🔎 2. Who claimed to be somewhere else but was not?

📸 Screenshot:
who_entered_ceo_office_&_false_alibi.png

➡️ Findings:

David Kumar entered the CEO Office between 20:50–21:00.

He also gave a false alibi, claiming he was in the Server Room while keycard logs prove otherwise.

📞 3. Who made or received calls around 20:50–21:00?
🧪 4. What evidence was found at the crime scene?

📸 Screenshot:
calls_&_evidence_at_scene.png

➡️ Findings:

A suspicious call happened at 20:55, involving David Kumar.

Evidence like fingerprints and keycard mismatch was found at the CEO Office shortly after the incident.

🧩 5. Identify the killer (final combined analysis)

To solve the case, I combined:

presence at the CEO’s Office during the crime window

false alibi check

call activity

evidence found at the scene

📸 Screenshots:
combined_analysis_ctes_part_1.png
combined_analysis_ctes_part_2.png

➡️ Final Result:

killer
David Kumar
🧠 How I arrived at the conclusion

The suspect was physically present inside the CEO Office at the critical time.

He provided a false alibi, which contradicts the keycard logs.

A phone call made by him during the crime window adds to suspicious behaviour.

Evidence at the crime scene aligns with his presence and movements.

Combining all factors clearly identifies David Kumar as the killer.

