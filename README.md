# bank-churn-analysis
## Summary 
Using a large dataset from a major bank company, the objective was to pull data using Pandas, evaluate and then create a basic prediction model of customer churn (indicated as '1' in 'Exited' columun). 
<br> *Note: I'm better at setting up the analysis using python and pulling business insights. Although it's not my main focus, I still find it useful to retain the basic steps of building a prediction model to think through what questions I need to consider.*</br>

<img width="900" alt="image" src="https://github.com/projecttiffany/bank-churn-analysis/assets/51961132/9ab9f06b-9be1-410a-b6bf-a727a814d1c8"><br>
<img width="362" alt="image" src="https://github.com/projecttiffany/bank-churn-analysis/assets/51961132/2e6bb6fe-4d85-49d9-a076-d34ad91a8b1b">
<br>*dataframe information*</br>

### Key Insights & Recommendations

#### Correlation Analysis of 'Exited' variable
<img width="920" alt="image" src="https://github.com/projecttiffany/bank-churn-analysis/assets/51961132/0f4bebc0-987a-4c45-a157-08913e7294a5"><br>
- Creating a visualization with the Pearsons Correlation coefficient (x-axis) we can better understand which numerical variables are dependent on the Exited values.
- Age and Balance have a high positive correlation, therefore it is the most important metric to predicting loyal new customers. When analyzing the breakdown of gender and salary, the best demographic of customers who do not churn are men and women over 40 with estimated salaries of $100K.</br>

 <br><img width="181" alt="image" src="https://github.com/projecttiffany/bank-churn-analysis/assets/51961132/1367a15c-c3e9-480b-9828-131f23b5e7c9"></br>


  - All relationships between Exited variable for a birdseye view
<br><img width="753" alt="image" src="https://github.com/projecttiffany/bank-churn-analysis/assets/51961132/34e1ed86-8bc6-47de-b584-799ecd3276b0"></br>

