# 🏟️ FanEdge

Sports insights MVP project — built to demonstrate **product management artifacts** and **solution engineering skills**.  
This is part of my career growth roadmap (Sports-Tech Product & AI Solutions tracks).

---

## 🎯 Goals
- Build a simple sports data app (Python + Streamlit)
- Showcase product management artifacts (PRD, wireframes, case study)
- Demonstrate analytics, storytelling, and demo skills

---

## 📌 Features (MVP Scope)
- Select a fixture from a sample dataset
- Generate a quick **Insight Card** with:
  - Predicted outcome proxy (rule-based or simple model)
  - Top 2–3 factors (form, goals, shots proxy)
  - Confidence band + optional “Why?” explanation
- Simple chart (last 5 matches form trend)

---

## 🛠️ Tech Stack
- **Python** (pandas, matplotlib)
- **Streamlit** (for web app interface)
- **Figma** (wireframes & prototypes)
- **Notion** (PRD, roadmap, case studies)

---

## 📂 Repository Structure
fanedge/
│
├── README.md              # Overview (project goals, scope, roadmap)
│
├── data/                  # Raw + cleaned datasets
│   ├── raw/               # Original sports datasets (CSV, JSON)
│   └── processed/         # Cleaned / feature-engineered datasets
│
├── notebooks/             # Jupyter/Colab notebooks for exploration
│   ├── week1_basics.ipynb # Python warm-up exercises
│   ├── features.ipynb     # Feature extraction (form, rolling averages)
│   └── charts.ipynb       # Simple charts for insights
│
├── app/                   # Streamlit app files
│   ├── streamlit_app.py   # Main entrypoint for the app
│   └── components/        # Reusable UI parts (insight card, charts)
│
├── docs/                  # Product artifacts
│   ├── FanEdge_Charter_v1.md  # Week 1 charter
│   ├── PRD_FanEdge_v1.md      # Week 2 PRD
│   ├── wireframes/            # Exported images from Figma
│   ├── case_study_v1.md       # Draft case study
│   └── metrics_plan.md        # Success metrics & OKRs
│
├── tests/                 # (Optional) lightweight test scripts
│   └── test_features.py   # Unit tests for data functions
│
└── requirements.txt       # Python dependencies (pandas, streamlit, matplotlib)
