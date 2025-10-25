# Customer-Behavior-Analysis-
## Overview
This project performs a comprehensive **data-driven analysis of customer shopping behavior** using a real-world retail transaction dataset from Kaggle.  
The goal is to uncover key trends in **customer demographics, payment methods, spending habits, and shopping mall performance** to support better business and marketing decisions.
---
## Objectives
- Analyze customer demographics (age, gender, location, etc.)
- Identify top-performing shopping malls and payment methods
- Explore purchasing frequency and average spending patterns
- Derive insights to improve sales strategies and customer engagement
  
## Tech Stack
- **Python**: Core programming language  
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, PandasQL  
- **Data Source**: [Kaggle - Customer Shopping Dataset](https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset)  
- **Environment**: Google Colab / Jupyter Notebook  

---

## Workflow
1. **Data Collection**  
   - Dataset imported via `kagglehub`  
   - CSV file loaded using `pandas.read_csv()`

2. **Data Cleaning**  
   - Removed duplicates and handled missing values  
   - Standardized categorical features (e.g., gender, payment method)  
   - Parsed and formatted date/time columns  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized customer distribution by gender, mall, and payment type  
   - Examined price and quantity patterns  
   - Identified outliers and spending trends  

4. **Insights Generation**  
   - Highlighted the most popular payment methods  
   - Detected high-spending demographics  
   - Uncovered relationships between product price and quantity

---
## Dataset 
https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset 


## Key Insights
- Female customers showed slightly higher purchase frequency than males.  
- Credit card payments were the most common across malls.  
- A few malls dominated total revenue, suggesting potential for targeted promotions.  
- Spending behavior correlated strongly with visit frequency and payment type.
