# Statistical Analysis and Hypothesis Testing of E-Commerce Sales Using Python

## 📌 Project Overview

This project focuses on performing statistical analysis and hypothesis testing on E-Commerce sales data using Python. The main objective is to investigate whether average invoice revenue differs between the United Kingdom and Germany.

The project uses the Online Retail dataset and applies descriptive statistics, hypothesis testing, confidence interval analysis, and statistical visualization techniques.

## 🎯 Research Question

Does average invoice revenue differ between the United Kingdom and Germany?

## 🧪 Hypotheses

**Null Hypothesis (H₀):**  
There is no difference between the average invoice revenue of the United Kingdom and Germany.

**Alternative Hypothesis (H₁):**  
There is a difference between the average invoice revenue of the United Kingdom and Germany.

**Significance Level:** α = 0.05

## 📊 Statistical Methods

The following statistical techniques were used:

- Descriptive Statistics
- Welch's Independent Samples t-test
- 95% Confidence Interval
- Mann–Whitney U Test
- Statistical Data Visualization

## 📈 Key Results

| Metric | Result |
|---|---:|
| UK Invoice Count | 18,020 |
| Germany Invoice Count | 458 |
| UK Average Revenue | £499.541848 |
| Germany Average Revenue | £499.297817 |
| Mean Revenue Difference | £0.244031 |
| Welch's t-statistic | 0.007791 |
| Welch's p-value | 0.993786 |
| 95% CI | (-£61.25, £61.74) |
| Mann–Whitney U Statistic | 3,496,501 |
| Mann–Whitney p-value | 2.283502 × 10⁻⁸ |

## 🔍 Findings

Welch's t-test produced a p-value of 0.993786, which is greater than 0.05. Therefore, the null hypothesis was not rejected, and there was insufficient evidence of a difference in average invoice revenue.

The 95% confidence interval ranged from approximately -£61.25 to £61.74 and included zero.

However, the Mann–Whitney U test produced a p-value of approximately 2.283502 × 10⁻⁸, indicating statistically significant evidence of a difference in the relative invoice revenue distributions.

The results demonstrate that two groups can have very similar average values while having different distributions and levels of variation.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

## 📂 Project Structure

```text
Week3-Statistical-Analysis-Hypothesis-Testing/
│
├── notebooks/
│   └── ecommerce_hypothesis_testing.ipynb
│
├── report/
│   ├── final_report_week03.docx
│   └── statistical_results.csv
│
├── visualizations/
│   ├── average_revenue_comparison.png
│   ├── confidence_interval.png
│   ├── country_revenue_boxplot.png
│   └── revenue_histogram.png
│
└── .gitignore
