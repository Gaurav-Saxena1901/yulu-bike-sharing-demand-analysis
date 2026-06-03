# Yulu Bike-Sharing Demand Analysis (Business Case Study)

## 📌 Project Overview
Yulu is India’s leading micro-mobility service provider, offering unique electric vehicles for daily solo and sustainable commuting. Recently, Yulu has experienced significant dips in revenue. This project focuses on analyzing the factors influencing the demand for shared electric cycles in the Indian market to help Yulu optimize operations, improve bike availability, and maximize revenue.

## 📊 Business Problem & Questions To Answer
Yulu wants to understand:
1. Which variables (e.g., weather, season, working days, temperature) are statistically significant in predicting the demand for shared electric cycles?
2. How well do these variables describe and impact overall rental demand?

## 🛠️ Tech Stack & Methodology
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy
- **Data Analysis:** Exploratory Data Analysis (EDA), Univariate & Bivariate Analysis
- **Statistical Hypothesis Testing:**
  - **T-Test:** Check the impact of working days on rentals.
  - **ANOVA / Kruskal-Wallis Test:** Analyze demand across different seasons and weather conditions.
  - **Chi-Square Test:** Check dependency between categorical variables.

## 🔍 Key Insights & Statistical Findings
- **Weather Impact (Kruskal-Wallis Test):** Weather has a highly statistically significant effect on cycle rentals ($p \approx 0$). Rank-order distributions prove that rentals drastically drop during heavy rain/snow compared to clear days.
- **Seasonality:** Demand patterns shift noticeably across seasons, indicating peak periods that require higher inventory density.
- **Operational Variables:** Environmental factors like temperature and humidity show a strong correlation with user renting habits.

## 🚀 Actionable Business Recommendations
- **Dynamic Operational Scaling:** Scale down field operations, battery swapping tasks, and roadside tracking deployments during forecasted rainy or extreme weather days to save operational costs.
- **Inventory Optimization:** Prioritize full inventory placement and maximum fleet availability during clear weather windows and peak seasons to capture latent demand.
- **Targeted Marketing:** Design specific user incentives or subscription models during transitionary seasons to maintain steady revenue.

---
*To explore the complete data manipulation, visualizations, and rigorous statistical testing, check out the full [Jupyter Notebook](./Business_Case_Study_Yulu_Bike.ipynb).*


## Update README with project summary and insights
