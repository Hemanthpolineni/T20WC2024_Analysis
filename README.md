# 🏏 ICC T20 World Cup 2024 – Data Analysis & Insights

This project provides a comprehensive **data-driven analysis** of the ICC T20 World Cup 2024 using **Python (EDA)**.  
The goal is to uncover patterns behind **match outcomes**, analyze **team and player performances**, and visualize insights through statistical charts.

---

## 📊 Project Overview

Cricket analytics helps uncover hidden factors that influence match results.  
This analysis aims to:
- Clean and preprocess T20 World Cup match datasets.  
- Identify correlations between **toss**, **venue**, and **match outcome**.  
- Perform **exploratory data analysis (EDA)** to uncover performance trends.  
- Visualize batting, bowling, and team-level metrics to understand winning patterns.

---

## 🧰 Tools & Technologies Used

| Category | Tools |
|-----------|--------|
| Data Processing | Python, Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Notebook Environment | Jupyter Notebook |
| Reporting | Statistical Charts & EDA Outputs |

---

## 🧹 Data Cleaning

Key steps in preprocessing included:
- Loading and inspecting the match dataset.  
- Removing irrelevant or sparse columns.  
- Handling missing values in fields like **scores**, **toss decision**, and **venue**.  
- Standardizing column names for consistency.  
- Ensuring correct datatypes for numerical and categorical analysis.

> “A clean dataset ensures more accurate cricket insights and avoids misleading interpretations.”

---

## 📈 Exploratory Data Analysis (EDA)

Visualized and analyzed critical match-related metrics such as:

- **Team Win Distribution**  
  ![Team Wins](images/team_wins.png)

- **Toss Decision Impact**  
  ![Toss Impact](images/toss_impact.png)

- **Batting First vs Chasing Success Rate**  
  ![Batting vs Chasing](images/batting_chasing.png)

- **Venue-wise Average Scores**  
  ![Venue Scores](images/venue_scores.png)

> Teams winning the toss often chose to **field first**, but the success rate varied significantly by venue.

---

## 📊 Key Insights from the Analysis

- Batting first provided a better chance of defending scores at certain venues.  
- Some teams demonstrated strong **chasing capability**, showing high success in second innings.  
- Venue conditions played a key role in determining ideal strategies.  
- Player of the Match awards were concentrated among consistent top performers.  

---

## ⚙️ How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/T20-WC-Analysis.git
cd T20-WC-Analysis
