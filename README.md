Cricket Biomechanical & Aerodynamic Analysis

Understanding cricket performance is not only tactical but also biomechanical and physics-driven.
This project studies how release mechanics, aerodynamics, and pitch interaction influence:

bounce behavior

shot selection

scoring efficiency

wicket probability

bowling effectiveness

Using data-driven modeling and interactive visualizations, we connect sports physics + analytics + machine learning to evaluate optimal bowling strategies.

📂 Dataset

Source: Kaggle
🔗 https://www.kaggle.com/datasets/piyushsharma18/cricket-shot-selection

Key Features

Bowler Type

Ball Length

Ball Line

Speed (km/h)

Shot Type

Runs Scored

Wicket

Field Placement

Angle (release angle)

Bounce (cm)

Field Positions

These variables enable both:

Biomechanics analysis → angle, speed, bounce

Tactical analysis → length, line, field

Outcome modeling → runs, wickets

🎯 Research Questions
RQ1

How does release angle determine bounce height and scoring outcomes?

RQ2

Does higher kinetic energy increase wicket probability or scoring risk?

RQ3

Which release angles create difficult batting conditions?

RQ4

How does bounce height influence shot selection and success?

RQ5

Can we predict “good bowlers” using aerodynamic characteristics?

⚙️ Methods Used
Statistical

Correlation analysis

Grouped aggregation

Risk curves

Heatmaps

Physics-based

Kinetic energy modeling

Bounce–angle geometry

Trajectory visualization

Machine Learning

Logistic Regression

Random Forest classifier

Probability prediction of bowling effectiveness

Visualization

3D trajectory plots

Heatmaps

Chord diagrams

Sankey diagrams

Interactive HTML dashboards (Plotly/Flourish/Power BI)

📊 Key Findings
🟢 RQ1 — Angle vs Bounce

Finding:

Bounce shows a non-linear relationship with release angle

Correlation ≈ 0 (very weak)

Pitch hardness and surface conditions influence bounce more than angle

Insight:
Release angle alone does not control bounce height.

🟢 RQ2 — Kinetic Energy vs Risk

Finding:

Very high energy → higher average runs, fewer wickets

Medium energy → balanced risk/reward

Low energy → deceptive deliveries, higher wicket rate

Insight:
Energy shows a U-shaped risk curve, where extremes create different advantages.

🟢 RQ3 — Optimal Release Angle

Finding:

Near 0° release angle → most economical

Steeper angles → easier scoring

Slightly negative angles → harder for batters

Insight:
Flat trajectories reduce batting freedom and improve control.

🟢 RQ4 — Bounce vs Shot Selection

Finding:

Low bounce → aggressive cross-bat shots (pull/hook/flick)

Medium bounce → maximum scoring freedom

High bounce → defensive straight-bat play

Insight:
Higher bounce restricts attacking shots and favors bowlers.

🟢 RQ5 — Aerodynamic Prediction of Good Bowlers

We trained a model using:

Speed

Angle

Bounce

Length

Line

Bowler Type

Result

The model predicts bowling effectiveness probability and visualizes it in 3D:

Yellow → high performance zone

Dark → poor deliveries

Insight:
Successful bowlers cluster around:

moderate-high speed

controlled bounce

stable angle
