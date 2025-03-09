# Dataset Details

This dataset was from the [Pakistan Ecommerce Dataset](https://www.kaggle.com/code/nadianizam/pakistan-ecommerce-data/input) by Nadia Nizam. It contains 584,524 transaction records from March 2016 to August 2018

# Project Overview

This project analyzes a large e-commerce dataset from Pakistan to uncover key trends and insights into customer behavior, product preferences and payment methods. The goal of this project is to analyze customer purchasing behavior, payment preferences and product trends within Pakistan's e-commerce sector. The insights gained will help businesses refine their operations and improve customer engagement.

### **Methodology**
1. **Data Cleaning:**  
   - Handled missing values using imputation techniques (median for numerical, mode for categorical).  
   - Removed irrelevant columns and outliers using the IQR method.  
   - Converted timestamps into a DateTime format for easier trend analysis.  

2. **Exploratory Data Analysis (EDA):**  
   - Summary statistics (mean, median, standard deviation) for key variables.  
   - Visualizations using histograms, boxplots and bar charts to identify patterns and outliers.  
   - Correlation analysis to examine relationships between price, quantity ordered and order status.  

3. **Trend and Pattern Analysis:**  
   - Analyzed seasonal trends and category performance.  
   - Identified peak shopping periods and changes in payment methods over time.  

## Tools & Libraries
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib & Seaborn** – Data visualization  
- **Plotly** – Interactive visualizations  
- **Scikit-learn** – Machine learning models  
- **SciPy** – Statistical analysis  
- **Missingno** – Handling missing values  

---
## Sample Visuals
### Best-Selling Categories
![image](https://github.com/user-attachments/assets/44d75603-58c5-4194-9dd4-6f3ea38cd6f3)

### Cancellation Rate by Category
![image](https://github.com/user-attachments/assets/d0ffed19-987f-4b98-9ec8-a15bb91a34c9)

### Seasonal Trends
![image](https://github.com/user-attachments/assets/3bd6c659-36c1-415e-a673-d5e82a898ae9)

## Key Insights
- Fashion and electronics are the most popular categories.  
- Peak shopping periods align with major events like Eid and Black Friday.  
- High cancellation rates in categories like electronics suggest improvement opportunities.  

## Skills Used
- Data Cleaning and Preprocessing  
- Data Visualization  
- Statistical Analysis  
- Trend and Pattern Identification  
- Machine Learning (Logistic Regression, Clustering)  
