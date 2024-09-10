# Detecting-Strategic-anomalies-in-online-poker
Building AI course project

---

# Project Title:
Building AI Course Project - Opening Lead Cheaters in Bridge

---

## Summary:
This project aims to develop an AI system to assess and analyze opening leads in the game of bridge. The model will be trained on data from online bridge servers and used to detect anomalies in opening lead selections, potentially identifying players whose lead choices differ suspiciously from typical behavior.

---

# Background:
Since the COVID-19 pandemic, face-to-face (f2f) bridge has been largely replaced by online platforms, most notably BBO (Bridgebase Online). Online bridge lacks the oversight found in f2f games, leading to an increase in cheating cases. 

Nicolas Hammond has developed a method using a hand database and a double dummy solver to assess outcomes of opening leads. His method identifies exceptional opening leads, but our solution will go further by recognizing and flagging *anomalous* leads, helping to detect potential cheating.

The AI tool would not only help detect cheats but also provide insights into how top players choose their opening leads.

---

# How is it used?
1. #Training and Testing:**  
   Analysts will train the AI using pre-pandemic f2f tournament data, excluding convicted cheaters. This will help the model recognize normal and abnormal lead behaviors.
  
2. # Real-time Use:
   Post-training, analysts can input data from recent tournaments to detect anomalies in opening leads. The flagged deals will be passed through a double dummy solver to assess if the anomalies resulted in disproportionately better or worse outcomes. 

3.# Investigations:
   If anomalies consistently lead to unusually positive outcomes, further investigation into potential cheating will be warranted. The tool will speed up the process of identifying suspects for further manual analysis.

---
# Data Sources and AI Methods: 
- **Data Sources:**  
  Data from vugraph archives of online bridge servers, including the hands, auctions, and plays, especially the opening lead. Data played by convicted cheats will be excluded.
  
  # AI Methods :
  Machine learning algorithms will be trained to detect anomalies in opening leads, flagging decisions that are statistically unusual compared to the norm.

---

# Challenges :
- **Detecting Cheating:**  
  The project won't definitively prove cheating but will highlight pairs where the probability of cheating is higher. Analysts will still need to perform manual investigations.
  
- # Data Quality:
  Excluding data from convicted cheats and ensuring clean data may pose challenges during data collection.

---

# What’s Next? 
The tool will complement existing methods like the Nicolas Hammond database, becoming an additional resource for identifying potential cheating in online bridge games.
