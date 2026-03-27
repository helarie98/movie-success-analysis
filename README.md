#🎬 Movie Success Analysis

## Overview
This project analyzes a dataset of over 3,200 movies to identify the key factors that drive movie success. The analysis focuses on financial performance, audience engagement, and genre-based trends using Excel.

---

## Objectives
- Understand what defines a successful movie
- Analyze the relationship between budget and revenue
- Evaluate the impact of ratings on revenue
- Identify the most profitable and efficient movie genres

---

## 📊 Dataset
- Source: Kaggle (TMDB Movie Dataset)
- Initial size: ~4800 movies
- Cleaned dataset: 3203 movies

---

## Data Cleaning
Several preprocessing steps were performed to ensure data quality:
    • Removed unuseful columns
    • Removed movies with missing or zero budget/revenue
    • Handled missing or inconsistent entries in key columns
    • Simplified complex genre data into a single primary genre
    • Removed movies where budget < 100 000
    • Created new features:
        ◦ Profit = Revenue − Budget
        ◦ ROI (Return on Investment) = Revenue / Budget
        ◦ Release Month extracted from release date

We observed after data cleaning that we have lost 33,4% of the data, this implies that we have removed movies with missing financial data to ensure accurate ROI and profit calculation. These steps ensured that the dataset was reliable for analysis.
---

## Analysis

### Budget vs Revenue
![Budget vs Revenue](images/budget_vs_revenue.png)

A scatter plot analysis revealed a positive relationship between budget and revenue. However, the relationship showed high variability, indicating that while higher budgets increase the potential for higher revenue, they do not guarantee success.

---

### Ratings vs Revenue
![Ratings vs Revenue](images/ratings_vs_revenue.png)

The analysis showed a weak positive relationship between audience ratings and revenue. This suggests that higher-rated movies may perform slightly better, but ratings alone are not a strong predictor of financial success. In other words, high-quality movies do not always make the most money, some low-rated movies still generate high revenue.
---

### Summary statistics
![Ratings vs Revenue](images/ratings_vs_revenue.png)
A comparison between mean (~$122M) and median (~$56M) revenue indicated that the data is right-skewed. A small number of blockbuster movies generate extremely high revenue, significantly influencing the average. The mean ROI of ~5.14, indicates that the film industry showed strong return on investment on average, with movies generating approximately five times their production budget. A maximum ROI of ~426 implied that, some movies are extremely efficient investments.

### Genre Analysis
![Genre Analysis](images/genre_pivot.png)
![Genre Analysis](images/genre_pivot.png)
Genre-based analysis using pivot tables provided the following insights:
    • Animation movies have the highest average (~$298M) and median (~$293M) revenue, indicating strong and consistent financial performance
    • Documentary movies have the highest average ROI (~7.57), likely due to low production costs combined with moderate revenue
    • Western movies have the highest median ROI (~2.85), suggesting consistent efficiency across films in this genre
Additionally, Animation movies represent only about 3% of the dataset, indicating that their high performance should be interpreted carefully.

---

## Key Insights
Higher budgets are associated with higher revenue, but outcomes remain uncertain
    • Audience ratings have limited influence on financial success
    • A small number of blockbuster movies significantly impact average revenue
    • Different genres achieve success in different ways:
        ◦ Animation → high revenue performance
        ◦ Documentary → high ROI potential
        ◦ Western → consistent ROI efficiency
    • Success should be evaluated using multiple metrics, including profit and ROI, not revenue alone

---

## Business Implications
The findings suggest that investment decisions in the film industry should balance scale and efficiency. While high-budget productions can generate significant revenue, smaller-budget films may deliver better returns on investment. Additionally, genre selection plays a critical role, as different genres offer varying risk-return profiles.

## Tools Used
- Microsoft Excel
  - Data Cleaning
  - ◦ Feature engineering
  - Pivot Tables
  - Data Visualization
---

## 🚀 Conclusion
Movie success cannot be measured by revenue alone. A combination of financial performance and efficiency metrics provides a more accurate evaluation.

---
