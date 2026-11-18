# 🏏 ICC CricPredict AI

> **Dark Neon ML Cricket Analytics & Real-Time Match Predictor**  
> An advanced machine learning web application that simulates and predicts win probabilities for official ICC matches (Tests, ODIs, T20Is, WTC, and World Cups) using an XGBoost-based simulation engine.

---

## 🌟 Features

* **⚡ Real-Time & Upcoming ICC Match Tracking:** Monitor live matches with dynamic Net Run Rate (CRR/RRR) updates, recent form feeds, and upcoming fixtures across all major formats.
* **🤖 XGBoost ML Simulation Engine:** Powered by a multi-factor weighting pipeline that evaluates live match dynamics, team form, and environmental factors to output confidence-scored win probabilities.
* **🎮 AI Match Predictor Playground (Manual Sandbox):** An interactive playground allowing users to manually tweak parameters (Teams, Venue, Pitch Type, Weather/Dew, Toss, and Live Match State) to instantly see updated predictive outcomes.
* **📊 Granular Feature Importance Breakdown:** Transparent insight into how the model weighs variables:
  * **Live Match State (35%):** Current score, wickets lost, overs bowled, momentum, and target.
  * **Recent 5-Match ICC Form (25%):** Momentum from previous international outings.
  * **Format Head-to-Head (20%):** Historical matchup advantages.
  * **Pitch, Dew & Toss (20%):** Environmental conditions (e.g., seam-friendly, spin-heavy, or heavy dew chasing advantage).
* **👤 ICC Player Stats & Photo Lookup:** Quick database search for player profiles, career stats, formats played, and recent milestones.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Dark Neon Theme, Responsive Flexbox/Grid UI)
* **Scripting / Interactivity:** Vanilla JavaScript (Dynamic UI Binding, Auto-Simulation Handlers)
* **Machine Learning / Logic:** Python, Scikit-Learn / XGBoost Architecture (Simulated / Integrated pipeline)
* **Design System:** Custom Dark-Mode Glassmorphism Dashboard

---

## 🚀 Getting Started Locally

To run or inspect this project on your local machine, follow these simple steps:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/icc-cricpredict-ai.git](https://github.com/your-username/icc-cricpredict-ai.git)
