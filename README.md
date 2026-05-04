# ⚽ Premier League Football Performance Analysis

> A data-driven analysis of Premier League performance using visual analytics and machine learning to identify key factors behind match outcomes.

An end-to-end data analytics project...

---

## 📊 Project Overview

This project analyses football match data to identify key performance factors that influence match outcomes. It combines exploratory data analysis, statistical relationships, and machine learning models to uncover patterns in team performance.

---

## 🔍 Key Insights

- Successful shots are the strongest predictor of match outcomes  
- Possession and passing contribute, but are not decisive on their own  
- Teams cluster into distinct attacking and defensive performance profiles  
- Logistic regression achieved ~68% accuracy, with performance limited by class imbalance  

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy)
- Data Visualisation (Matplotlib, Seaborn)
- Scikit-learn (Clustering, Logistic Regression)
- Jupyter Notebook

---

## 📈 Visualisations

### Total Score by Team
Clear performance gaps exist between top and bottom teams, highlighting overall competitiveness in the league.
![Total Score](images/total-score.png)

### Correlation Between Metrics
Successful shots show the strongest relationship with match outcomes, while possession has a weaker impact than expected.
![Correlation Heatmap](images/correlation-heatmap.png)

### Team Performance Heatmap
Reveals differences in team play styles, particularly between attacking and defensive performance metrics.
![Performance Heatmap](images/performance-heatmap.png)

### Clustering Evaluation
Groups teams into performance-based clusters, highlighting similarities in playing style and effectiveness.
![Clustering](images/clustering.png)

### Distribution of Key Metrics
Shows variability in match statistics, with certain metrics displaying significant spread across teams.
![Distribution](images/distribution.png)

---

## 🤖 Analytical Approach

- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Correlation analysis  
- Clustering (K-Means, Hierarchical)  
- Logistic Regression  

---

## ⚠️ Limitations

- Model performance affected by class imbalance  
- Limited predictive accuracy (~68%)  
- Could be improved with more advanced models  

---

## 🚀 Future Improvements

- Apply SMOTE to balance classes  
- Use Random Forest / XGBoost  
- Hyperparameter tuning  
- Build an interactive dashboard (Streamlit)  

---

## 📁 Repository Contents

- `football-performance-analysis.ipynb` — main analysis  
- `premierLeague.xlsx` — dataset  
- `report.pdf` — full written report  
