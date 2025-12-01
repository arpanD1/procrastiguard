
# ProcrastiGuard – Multi-Agent Study & Procrastination Assistant

ProcrastiGuard is a **multi-agent AI system** designed to help students plan their studies, track real study behavior, detect procrastination patterns, and receive personalized interventions to improve productivity and consistency.

This project is built using **Google Agent Development Kit (ADK)** and the **Gemini LLM**.

---

## 📌 Problem Statement

Many students create study plans but fail to follow them consistently due to:
- Procrastination
- Distractions (especially mobile phones)
- Lack of feedback on real study behavior
- No personalized corrective guidance

There is a need for an **intelligent system** that not only plans but also **monitors behavior and gives adaptive feedback**.

---

## ✅ Solution Statement

ProcrastiGuard solves this by using a **multi-agent AI workflow** that:
1. Creates a realistic exam study plan.
2. Records what actually happens in each study session.
3. Detects the level and type of procrastination.
4. Suggests practical interventions for the next session.
5. Stores history for long-term improvement.

---

## 🧠 System Architecture

### High-Level Workflow

User Input → Planner Agent → Study Session Agent → Behavior Classifier Agent → Intervention Agent → Session History

---

## 🤖 Agents Description

### 1️⃣ Planner Agent
- Creates a **difficulty-aware exam study plan**
- Allocates more time to harder subjects
- Produces a clear day-wise or subject-wise schedule

### 2️⃣ Study Session Agent
- Records planned vs actual study behavior
- Outputs a structured `SESSION SUMMARY`

### 3️⃣ Behavior Classifier Agent
- Detects procrastination type and severity

### 4️⃣ Intervention Agent
- Suggests personalized actions for the next session

---

## 🛠 Tech Stack

- Python
- Google Agent Development Kit (ADK)
- Google Gemini LLM
- Jupyter Notebook

---

## 🔐 API Key Security

API keys are not stored in the notebook. Users must provide their own keys securely.

---

## ▶️ How to Run the Project

1. Add `GOOGLE_API_KEY` in Kaggle Secrets.
2. Open `procrastiguard.ipynb`.
3. Run all cells from top to bottom.
4. View session summary, diagnosis, and intervention.

---

## 📂 Project Structure

procrastiguard/
├── procrastiguard.ipynb
├── README.md
├── requirements.txt
└── assets/

---

## 👤 Author

Arpan Dutta
