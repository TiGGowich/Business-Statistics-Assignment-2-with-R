# CVD and Customer Satisfaction Analysis: Exploring Statistical Relationships Using R

This repository contains a two-part statistical analysis project completed as part of my MSc in Business Analytics at Warwick Business School (WBS). The project uses publicly available datasets to investigate the following:

1. The relationship between socio-economic and lifestyle factors and Cardiovascular Disease (CVD) prevalence in England.
2. The drivers of customer satisfaction for a retail furniture company, with a focus on delivery time and socio-economic context.

The assignment was completed using R and applies core statistical methods to draw business-relevant conclusions.

---

## 📂 Repository Contents

- [**`cvd_and_satisfaction_analysis.rmd`**](./cvd_and_satisfaction_analysis.rmd): Full R Markdown source code containing all data loading, EDA, analysis, and visualizations.
- [**`cvd_and_satisfaction_analysis.html`**](./5652632.html): Knitted HTML report with results and business-focused insights.
- [**`Cardio_Vascular_Disease.csv`**](./Cardio_Vascular_Disease.csv): Public health dataset used in Question 1.
- [**`cust_satisfaction.csv`**](./cust_satisfaction.csv): Public retail customer satisfaction dataset used in Question 2.

---

## 📊 Dataset Information

**1. Cardio_Vascular_Disease.csv**
- Source: UK Office for National Statistics
- Scope: Local authority regions in England
- Key variables: CVD prevalence, obesity rate, poverty level, smoking rate, wellbeing score, population size

**2. cust_satisfaction.csv**
- Source: Furniture retail company (anonymized)
- Scope: Store-level observations
- Key variables: Customer satisfaction, staff job satisfaction, delivery times, socio-economic store classification, product range

These datasets are publicly accessible and are exclusively used for academic and analytical purposes.

---

## 🧠 Project Overview

### 🩺 Question 1 – Cardiovascular Disease

**Objective**: Determine which socio-economic and health-related factors are statistically associated with CVD prevalence across English regions.

**Approach**:
- Clean and validate the dataset
- Perform exploratory data analysis (EDA)
- Fit linear regression models
- Interpret statistical significance and effect sizes
- Create a professional visualization of the poverty-CVD relationship

---

### 🛍️ Question 2 – Customer Satisfaction

**Objective**: Identify key drivers of customer satisfaction, especially the role of delivery times, and assess whether this effect varies across socio-economic statuses (SES).

**Approach**:
- Clean and validate the dataset
- Conduct EDA
- Fit multiple regression models including interaction terms
- Focus on how delivery delays affect satisfaction across SES tiers
- Present findings in plain language and through a clear plot

---

## 🧰 Methods and Tools

- **Language**: R
- **Libraries**: `tidyverse`, `ggplot2`, `dplyr`, `lubridate`, `gridExtra`, `kableExtra`, `scales`
- **Techniques**: Data cleaning, EDA, regression analysis, ANOVA, interaction terms, professional visualization
- **Outputs**: Summary statistics, diagnostic plots, regression results, business recommendations

---

## ✅ Results Summary

### Cardio Vascular Disease (CVD) Analysis:
- Only **23.9% of the variance** in CVD prevalence is explained by the model including poverty, obesity, smoking rates, and wellbeing scores. This indicates that a substantial **76% of variance remains unexplained**, suggesting additional variables are required for a more robust model.
- Of the predictors, **poverty and obesity** showed a statistically significant positive association with CVD rates.
- A professional plot illustrates the positive linear relationship between poverty levels and CVD prevalence across regions.

### Customer Satisfaction Analysis:
- Delivery time has a **statistically significant negative effect** on customer satisfaction overall.
- An interaction effect was identified between **delivery time and store SES classification**:
  - In **high SES stores**, customer satisfaction **declines sharply** as delivery times increase.
  - In contrast, **low SES stores** show **only a modest decrease** in satisfaction with longer delivery times.
- This suggests that **customer expectations differ by SES group**, and that **high SES customers are more sensitive to delays**—a finding with strong implications for delivery strategy segmentation.

---

## 📎 How to Use This Repository

You can:
- Open the `.rmd` file in RStudio to view, modify, and rerun the code.
- Open the `.html` file in your browser to see the final report with explanations and visualizations.

---

## 📬 Contact

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/benjamin-sachse-consultant/) or reach out for collaboration opportunities!

