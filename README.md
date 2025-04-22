# 🧠 Premier League Midfielder Analysis

This project compares five elite Premier League midfielders using real match data to explore both creative and defensive attributes. It's a showcase of data analysis, football intelligence, and visualization in Python.

## ⚽ Players Analyzed
- Bruno Fernandes (Manchester United)
- Kevin De Bruyne (Manchester City)
- Rodri (Manchester City)
- Declan Rice (Arsenal)
- Martin Ødegaard (Arsenal)

---

## 📊 Metrics Compared

### 🎨 Creative Metrics (Radar Chart)
- Expected Assists (xAG)
- Shot-Creating Actions (SCA)
- npxG + xAG
- Progressive Passes
- Progressive Carries
- Touches in Attacking Penalty Area

### 🛡️ Defensive/Physical Metrics (Radar Chart)
- Tackles
- Interceptions
- Aerials Won
- Clearances
- Blocks
- Successful Take-Ons

---

## 📈 Visuals

### Creative Metrics Radar  
<img src="visuals/attacking_radar.png" width="600"/>

### Defensive Metrics Radar  
<img src="visuals/defensive_radar.png" width="600"/>

---

## 💻 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebooks
- Git & GitHub
- Data source: [FBref.com](https://fbref.com/)

---

## 🧠 Key Insights

- **De Bruyne** leads in creativity (xAG, SCA, final-third involvement).
- **Bruno** shows elite creative output with significant shot involvement.
- **Rodri** is a midfield metronome — top for progressive passes and highly defensive.
- **Rice** is balanced — contributes defensively and carries forward.
- **Ødegaard** is a positional, technical operator — high in progressive actions but less involved in duels.

---

## 📂 Folder Structure

midfield-analysis/
├── data/          # Raw data files (player_stats.csv)
├── notebooks/     # Jupyter notebooks (visualizations, analysis)
├── visuals/       # Exported radar charts
└── README.md      # Project summary

---

## 📌 Future Improvements

- Add interactive dashboards (Plotly, Streamlit)
- Expand player pool and include more roles
- Explore match-by-match trends
