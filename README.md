# Task_06_Descriptive_Stats_Part2

> Syracuse University — OPT Progress  
> Reporting Period: **Second Half of Task 5 (Task 6)**

---

## 📌 Overview

This project continues **Task 5: Descriptive Statistics & LLMs**, focusing on **prompt refinement, evaluation, and conclusions** using the **2025 Syracuse Women’s Lacrosse** season stats.  
Two LLMs — **ChatGPT** and **Claude** — were compared on the same set of natural language questions, with results validated against the official dataset.

---

## 🧭 Objectives

1. Refine prompts from Task 5 and reduce ambiguity.  
2. Query **two LLMs** (ChatGPT & Claude) on descriptive statistics questions.  
3. Compare responses to dataset-derived ground truth.  
4. Document convergence, divergence, and reasons.  
5. Conclude with coaching recommendations supported by the data.  

---

## ❓ Questions Asked

1. How many games did Syracuse Women’s Lacrosse play in the 2025 season, and what was the overall win–loss record?  
2. Which player scored the most goals, and how many did she score?  
3. Which player had the highest shooting percentage?  
   - Use goals/shots.  
   - Only consider players with ≥25 total shots.  
4. Who was the most improved player over the 2025 season, and what data supports that claim?  
5. If the coach wants to win 2 more games next season, should the team focus on offense or defense, and which one player should be the game changer?  

---

## 🤖 LLM Responses

### Q1. Games & Record  
- **ChatGPT:** 19 games, 10–9 record ✅  
- **Claude:** 19 games, 10–9 record ✅  

### Q2. Top Scorer  
- **ChatGPT:** Emma Muchnick – 34 goals ✅  
- **Claude:** Emma Muchnick – 34 goals ✅  

### Q3. Highest Shooting % (≥25 shots)  
- **ChatGPT:** Ranked Muchnick (47.9%), Trinkaus (44.4%), Ward (39.0%). → Answer: **Muchnick** ✅  
- **Claude:** Same ranking. → Answer: **Muchnick** ✅  

### Q4. Most Improved Player  
- **ChatGPT:** Insufficient data; prior-season stats needed.  
- **Claude:** Same; flagged need for prior-season data.  

### Q5. Coaching Focus & Game-Changer  
- **ChatGPT:** Focus on defense & possession. Game-changer: **Goalie Daniella Guyette** (improving save %).  
- **Claude:** Focus on draw controls & goalie performance. Game-changers: **Meghan Rode** (75 draw controls) and **Guyette** (save %).  

---

## 🔬 Comparison

- Both LLMs answered **Q1–Q3** correctly and consistently.  
- Both appropriately refused to fabricate an answer for **Q4**, noting lack of data.  
- For **Q5**, both emphasized possession and defensive efficiency, but:  
  - ChatGPT focused on **goalie save %**.  
  - Claude added **draw controls (Rode)** alongside goalie improvement.  

---

## ✅ Conclusion

- **Reliability:** Both LLMs handled descriptive statistics questions well when prompts included clear thresholds (≥25 shots).  
- **Limits:** Neither model invented a “most improved” player — correctly identifying missing data.  
- **Insight:** Syracuse already outscored opponents on average, but the **–40 draw-control deficit** and **.433 save %** were critical weaknesses.  
- **Recommendation:** Coaching efforts should prioritize **possession (draw controls)** and **goalie training**, as these factors could flip narrow losses into wins.  

---
