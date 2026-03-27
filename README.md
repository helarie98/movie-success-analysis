# 🎬 Movie Success Analysis

## 📖 Overview
This project analyzes a dataset of over 3,200 movies to identify the key factors that drive movie success. The analysis focuses on financial performance, audience engagement, and genre-based trends using Excel.

---

## 🎯 Objectives
- Understand what defines a successful movie
- Analyze the relationship between budget and revenue
- Evaluate the impact of ratings on revenue
- Identify the most profitable and efficient genres

---

## 📊 Dataset
- Source: Kaggle (TMDB Movie Dataset)
- Initial size: ~4800 movies
- Cleaned dataset: 3230 movies

---

## 🧹 Data Cleaning
- Removed movies with missing or zero budget/revenue
- Cleaned and simplified genre column
- Created new features:
  - Profit = Revenue − Budget
  - ROI = Revenue / Budget
  - Release Month

---

## 📈 Analysis

### Budget vs Revenue
![Budget vs Revenue](images/budget_vs_revenue.png)

- Positive relationship with high variability
- High budget increases potential but not guaranteed success

---

### Ratings vs Revenue
![Ratings vs Revenue](images/ratings_vs_revenue.png)

- Weak positive relationship
- Ratings alone do not determine financial success

---

### Genre Analysis
![Genre Analysis](images/genre_pivot.png)

- Animation: highest revenue (average & median)
- Documentary: highest average ROI
- Western: highest median ROI

---

## 🧠 Key Insights
- Revenue is driven by multiple factors, not just budget or ratings
- ROI is a critical metric for evaluating efficiency
- Different genres succeed in different ways
- A small number of blockbuster movies skew averages

---

## 💼 Tools Used
- Microsoft Excel
  - Data Cleaning
  - Pivot Tables
  - Data Visualization

---

## 🚀 Conclusion
Movie success cannot be measured by revenue alone. A combination of financial performance and efficiency metrics provides a more accurate evaluation.

---

## 📁 Project Structure
