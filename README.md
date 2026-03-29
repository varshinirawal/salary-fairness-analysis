Project Title :
Salary Prediction and Fairness Analysis Across Job Roles and Locations

Problem Statement:
This project aims to predict salaries based on various features and analyze whether salary distribution is
fair across different job roles and locations.The goal is to identify inconsistencies in compensation 
and highlight roles that are more affected by salary imbalance.

Approach:
Performed Exploratory Data Analysis (EDA) to understand the dataset
Applied One-Hot Encoding for categorical variables
Used Standard Scaling for numerical features
Built a Linear Regression model to predict salaries
Calculated salary gap (difference between actual and predicted salary)
Classified salary into fair, underpaid, and overpaid categories
Analyzed salary inconsistency across job roles and locations

Key Findings:
The model achieved a good prediction performance with a low average error (~5%)
Overall salary gaps appear small, but deeper analysis reveals location-based inconsistencies
Certain roles such as Data Analyst and Business Analyst show higher instability across multiple locations
Salary fairness is not uniform and varies significantly depending on geographic region
Some roles experience consistent underpayment or overpayment depending on location

Visualizations:
Bar Chart → Shows roles with highest salary inconsistency across locations
Heatmap → Highlights location-wise distribution of underpaid roles

Tools & Technologies:
Python
Pandas
NumPy
Scikit-learn
Seaborn & Matplotlib

Conclusion
The model successfully predicts salaries with good accuracy; however, fairness analysis reveals that 
compensation consistency varies across locations. Certain job roles exhibit higher salary instability,
indicating that geographic factors play a significant role in salary distribution. This highlights the
need for more standardized and fair compensation structures across regions
