Churn Analysis EDA
This repository contains an exploratory data analysis (EDA) of customer churn data. The goal of this project is to analyze the data, identify key factors contributing to customer churn, and provide insights for reducing churn rates.

About the Data
The dataset used in this analysis is a sample customer dataset from a telecom company. The dataset contains 7043 rows and 21 columns, including customer information, service usage, and churn status.

EDA Process
The EDA process involved the following steps:

1. Data Loading and Cleaning
The dataset was loaded into a Pandas dataframe and cleaned by handling missing values, encoding categorical variables, and scaling numerical variables.

2. Data Visualization and Exploration
Various visualization techniques were used to explore the data, including:

Histograms and density plots to understand the distribution of numerical variables
Bar charts and heatmaps to analyze categorical variables
Scatter plots to identify correlations between variables
Box plots to visualize the distribution of variables by churn status
3. Feature Engineering and Selection
New features were engineered by combining existing variables, and feature selection was performed using correlation analysis and recursive feature elimination.

4. Correlation Analysis and Feature Importance
Correlation analysis was performed to identify the most important features contributing to customer churn. Feature importance was calculated using a random forest classifier.

Findings
The EDA revealed several key insights into customer churn behavior. The most important factors contributing to churn were:

Total Charges: Customers with higher total charges are more likely to churn.
Tenure: Customers with shorter tenure are more likely to churn.
Internet Service: Customers with fiber optic internet service are less likely to churn.
Phone Service: Customers with phone service are more likely to churn.
Multiple Lines: Customers with multiple lines are less likely to churn.
Conclusion
This EDA provides a comprehensive analysis of customer churn data and identifies key factors contributing to churn. The insights gained from this analysis can be used to develop targeted strategies for reducing churn rates and improving customer retention.

License
This repository is licensed under the MIT License.

Contributing
Contributions to this repository are welcome. Please submit a pull request with your proposed changes.

Acknowledgments
I would like to thank Kaggle for providing the dataset and the Python data science community for their support and resources.

Contact
For questions or feedback, please contact hiteshnitkkr.

Files
churn_data.csv: The customer churn dataset
eda.ipynb: The Jupyter notebook containing the EDA code
README.md: This README file
Technologies Used
Python 3.8
Pandas 1.2.4
NumPy 1.20.0
Matplotlib 3.4.2
Seaborn 0.11.2
Scikit-learn 0.24.2
