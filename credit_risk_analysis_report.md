 # Credit Risk Analysis Report  
   
 ## Overview  
   
 In this analysis, I used historical lending data to build a logistic regression model. The goal was to predict whether a loan is healthy (0) or high-risk (1). I took a simple, step-by-step approach using basic Python to ensure I understood each part of the process.  
   
 ## Model Performance  
   
 - **Accuracy:** 99%  
 - **Precision:**   
   - Healthy Loans (0): 100%  
   - High-Risk Loans (1): 85%  
 - **Recall:**   
   - Healthy Loans (0): 100%  
   - High-Risk Loans (1): 91%  
   
 ## Summary and Recommendation  
   
 The logistic regression model performed very well:  
 - It almost perfectly identifies healthy loans.  
 - It correctly identifies 91% of the high-risk loans, even though the precision for high-risk loans is 85%.  
   
 Based on these results, I recommend using this model as part of a broader loan evaluation system rather than the sole decision-making tool. This combination approach can help ensure that potential high-risk loans are not overlooked.  