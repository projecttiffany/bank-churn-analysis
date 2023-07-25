# bank-churn-analysis
## Summary 
Using a large dataset from a major bank company, the objective was to pull data using Pandas, evaluate and then create a basic prediction model of customer churn (indicated as '1' in 'Exited' columun). 
<br> *Note: I'm better at setting up the analysis and pulling business insights using python. Although data science is not my main focus, I still find it useful to retain the basic steps of building a prediction model to think through what questions I need to consider.*</br>

![image](https://github.com/projecttiffany/bank-churn-analysis/assets/51961132/2fd1a6e3-c3c7-409b-bfe2-b7743371ea1c)<br>
![image](https://github.com/projecttiffany/bank-churn-analysis/assets/51961132/6cb9229b-e1e7-4fb5-97ac-87433fae2a4c)</br>

<br>*dataframe information*</br>

### Key Insights & Recommendations

### Correlation Analysis of 'Exited' variable
![image](https://github.com/projecttiffany/bank-churn-analysis/assets/51961132/f5e8f591-04c4-48e9-b6ac-3cc2bdb892ec)<br>
- Creating a visualization with the Pearsons Correlation coefficient (x-axis) we can better understand which numerical variables are dependent on the Exited values.
- Age and Balance have a high positive correlation, therefore it is the most important metric to predicting loyal new customers. When analyzing the breakdown of gender and salary, the best demographic of customers who do not churn are men and women over 40 with estimated salaries of $100K.

  ![image](https://github.com/projecttiffany/bank-churn-analysis/assets/51961132/9bb0d215-3dc0-4c05-a3ca-07c6f4313cbd)<br>

  - All relationships between Exited variable
![image](https://github.com/projecttiffany/bank-churn-analysis/assets/51961132/c859f207-ed8f-430d-9d1c-f77477b4d9c8)
