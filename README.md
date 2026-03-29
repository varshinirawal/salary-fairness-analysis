Project Title :<br>
Salary Prediction and Fairness Analysis Across Job Roles and Locations
<br>
Problem Statement:<br>
This project aims to predict salaries based on various features and analyze whether salary distribution is
fair across different job roles and locations.The goal is to identify inconsistencies in compensation 
and highlight roles that are more affected by salary imbalance.

Approach:<br>
Performed Exploratory Data Analysis (EDA) to understand the dataset <br>
Applied One-Hot Encoding for categorical variables<br>
Used Standard Scaling for numerical features<br>
Built a Linear Regression model to predict salaries<br>
Calculated salary gap (difference between actual and predicted salary)<br>
Classified salary into fair, underpaid, and overpaid categories<br>
Analyzed salary inconsistency across job roles and locations<br>

Key Findings:<br>
The model achieved a good prediction performance with a low average error (~5%)<br>
Overall salary gaps appear small, but deeper analysis reveals location-based inconsistencies<br>
Certain roles such as Data Analyst and Business Analyst show higher instability across multiple locations <br>
Salary fairness is not uniform and varies significantly depending on geographic region<br>
Some roles experience consistent underpayment or overpayment depending on location<br>

Visualizations:<br>
Bar Chart → Shows roles with highest salary inconsistency across locations<br>
Heatmap → Highlights location-wise distribution of underpaid roles<br>

Tools & Technologies:<br>
Python<br>
Pandas<br>
NumPy<br>
Scikit-learn<br>
Seaborn & Matplotlib<br>

Conclusion: <br>
The model successfully predicts salaries with good accuracy; however, fairness analysis reveals that 
compensation consistency varies across locations. Certain job roles exhibit higher salary instability,
indicating that geographic factors play a significant role in salary distribution. This highlights the
need for more standardized and fair compensation structures across regions
