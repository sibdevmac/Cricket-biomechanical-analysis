# 🏏 Cricket Biomechanical Analysis

## 📌 Project Overview
This project explores **cricket biomechanics and sports physics** to understand how bowling mechanics influence ball behavior, shot selection, and match outcomes.

Using trajectory physics, kinetic energy calculations, and statistical analysis, we study how **release angle, bounce height, and ball energy** affect:

- Runs scored
- Wicket probability
- Shot difficulty
- Bowling effectiveness

The goal is to apply **data science + sports analytics** to derive performance insights for bowlers and batters.

---

## 📂 Dataset

**Source:** Kaggle – Cricket Shot Selection Dataset  
Link: https://www.kaggle.com/datasets/piyushsharma18/cricket-shot-selection

The dataset includes biomechanical and match-related features such as:

- Release angle
- Velocity
- Kinetic energy
- Bounce height
- Shot type
- Runs scored
- Wickets
- Ball outcomes

---

## ❓ Research Questions

This project answers the following:

### RQ1
How does release angle determine bounce height and scoring outcomes?

### RQ2
Does higher kinetic energy increase wicket probability or scoring risk?

### RQ3
Which angle creates difficult batting conditions?

### RQ4
How does bounce height influence shot selection and success?

### RQ5
Can we build an aerodynamic prediction model for identifying the best bowlers?

---

## 🧠 Methodology

- Exploratory Data Analysis (EDA)
- Heatmaps
- Kinetic energy modeling (½mv²)
- Angle vs bounce trend analysis
- Interactive visualizations

---

## 📊 Key Findings

### ✅ RQ1 — Release Angle vs Bounce Height
- Bounce height first increases, then decreases, and rises again with angle.
- Release angle alone does **not directly control bounce**.
- Surface hardness and pitch conditions are stronger contributors.

**Conclusion:** Angle affects trajectory more than bounce physics.

<img width="576" height="538" alt="image" src="https://github.com/user-attachments/assets/d0c571b9-350e-458d-9492-5433cb1120d6" />

---

### ✅ RQ2 — Kinetic Energy vs Match Outcomes
- Very high energy → higher average runs, fewer wickets
- Medium energy → balanced performance
- Very low energy → higher wickets due to deception

**Conclusion:** Slower or deceptive deliveries can increase wicket probability.

---

### ✅ RQ3 — Optimal Release Angle
- Low release angles create tougher batting conditions
- 10–12° angles increase scoring chances
- Around 0° is the most economical bowling zone

<img width="629" height="468" alt="image" src="https://github.com/user-attachments/assets/d979b277-117b-4b36-abef-b89af755d299" />

**Conclusion:** Flatter trajectories benefit bowlers.


---

### ✅ RQ4 — Bounce Height vs Shot Selection

| Bounce Height | Batting Behavior | Advantage |
|-------------|-----------------|-----------|
| Low         | Aggressive cross-bat shots | Batter |
| Medium      | Free scoring             | Neutral |
| High        | Defensive straight bat   | Bowler |

<img width="785" height="590" alt="image" src="https://github.com/user-attachments/assets/dfdc09a0-64c4-4f59-b855-c6b0b73ba089" />

**Conclusion:** Higher bounce favors bowlers and reduces scoring freedom.

---

### ✅ RQ5 — Aerodynamic Bowler Prediction
- Successful bowlers show:
  - Lower median runs
  - Controlled energy output
  - Stable release mechanics
- Visual clustering identifies high-performance zones

**Conclusion:** Consistency + controlled aerodynamics define effective bowlers.

---

## 👤 Author
Sibankar Saha
