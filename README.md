# 🛒 E-commerce Customer Behavior EDA

## Project Overview

This project explores and analyzes an e-commerce customer behavior dataset. The analysis aims to uncover patterns in customer demographics, purchasing activity, engagement, and satisfaction levels. Insights from this project can help guide marketing strategies, customer targeting, and business decisions.

---

## Dataset Description

- **Source:** Cleaned CSV file with 348 entries (after removing missing/duplicate values)
- **Key Columns:**
  - **Customer demographics:** ID, Gender, Age, City
  - **Purchase details:** Membership Type, Total Spend, Items Purchased
  - **Engagement metrics:** Average Rating, Discount Applied, Days Since Last Purchase
  - **Satisfaction Level:** Target variable (Unsatisfied, Neutral, Satisfied)

---

## EDA Summary

- **Age Distribution:**  
  Most customers are aged 28–36. Satisfied customers tend to be slightly older.

- **Satisfaction & Spend:**  
  Satisfied customers spend significantly more on average. Higher spending aligns with higher satisfaction.

- **Correlation:**  
  Age has a weak correlation with other features. The strongest positive correlation is between Total Spend and Items Purchased.

- **Membership Type:**  
  Gold members are more likely to be satisfied and spend more, while Bronze members have a higher proportion of unsatisfied customers.

- **Items Purchased:**  
  Customers who purchase more items are generally more satisfied.

- **Age Group Segmentation:**  
  The 25–35 and 36–45 age groups show higher satisfaction and higher average spend.

- **City/Location:**  
  Some cities have a higher proportion of satisfied customers and higher average spend.

- **Discount Impact:**  
  Discounts are associated with higher satisfaction and increased spending.

- **Data Quality:**  
  No missing values or duplicate rows. Data types are appropriate for analysis.

---

## How to Use

1. Open the Jupyter Notebook (`customers_behavior.ipynb`) in VS Code or Jupyter Lab.
2. Run the cells step by step to reproduce the EDA and visualizations.
3. Review the summary and insights for actionable business recommendations.

---

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn

Install requirements with:
```bash
pip install pandas matplotlib seaborn
```

---

## License

This project is for educational and analytical purposes.
