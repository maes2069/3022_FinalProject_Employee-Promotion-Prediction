# HR-Analytics-Bayesian-Classification  
CSPB 3022 Final project: HR Analytics - Employee Promotion Data, Bayesian Classification  
Margarita Espinoza [maes2069@colorado.edu]  
CSPB 3022 - Spring 2023  

### Project Topic  

*Note: My project topic has changed since submitting part 1*

**PART 1 SUBMISSION:**  
This project is a classification problem, set to predict whether an employee in the dataset is likely to be promoted or not after the EDA process. This problem is important to solve because it makes the internal hiring process more efficient AND it allows hiring managers to see ALL potential candidates based on performance data. In addition, I would like to discover patterns and outliers related to gender, age, education, and department.  

My goal is to predict if a candidate is likely to receive a promotion or not and to use that information to add a column named 'promotion_likely' with a binary yes/no identifier for each candidate.

**PART 2 SUBMISSION:**  
This dataset was collected to predict whether an employee in a mulit-national company is likely to be promoted or not after the EDA process. There were 2 datasests included in the Kaggle repository, one before the promotion prediction and one after that includes the binary 'is_promoted' column. My initial thought was to perform a binary classification algorithm to predict wheter each employee is likely to be promoted or not and then compare it to the data in the 'is_promoted' column, which is described above in the 'PART 1 SUBMISSION' section. 

Instead of attempting to predict if an employee will be pomoted or not, I will be using Naive Bayesian Classification and target feature 'is_promoted' to determine the probability of being promoted given different attributes such as gender, education, trainings, awards, and years of service.

My goal is to learn details about this company's promotion criteria and how features related to things that are controllable by the employee (such as education) and not controllable (like age and gender) impact their probability of being promoted.
