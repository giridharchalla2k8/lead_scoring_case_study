**Lead Scoring Case Study**
-----------------------------

**Problem Statement**

An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses. They have process of form filling on their website after which the company that individual as a lead. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc.Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%. Now, this means if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as Hot Leads.If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone

**Business Objective**

Lead X wants us to build a model to give every lead a lead score between 0 -100 . So that they can identify the Hot leads and increase their conversion rate as well. The CEO want to achieve a lead conversion rate of 80%. They want the model to be able to handle future constraints as well like Peak time actions required, how to utilize full man power and after achieving target what should be the approaches.

**Approach taken for Solution**

 - Importing libraries and dataset
 - Data cleaning and data manipulation
    - Check for imbalanced data
    - Check for columns with Select value and Impute the data
    - Check for duplicate data
    - Check for  missing values and impute/drop the columns
    - Check for outliers and impute data
 - Exploratory data analysis
   - Univariate analysis
   - Bivariate analysis
 - Data Preparation
   - Dataset split into Train and Test sets
   - Feature scaling and Dummy variables and encoding the data
 - Model Building using RFE and make use of StatsModel
   - Build logistic regression model and delete the variables which are not useful using the p-value and VIF values
 - Model Evaluation
   - Confusion Matrix and ROC curve
   - Optimal cutoff point for Accuracy Sensitivity and Specificity	
 - Model Prediction on test dataset
 - Precision and Recall View
   - Precision and Recall tradeoff
 - Model Prediction on test dataset

**Details of files given**

- Lead Score Case Study .ipynb : The python file showing coding and data analysis
- Assignment Subjective Questions.pdf : Some subjective questions answered
- Lead Score Case Study.pdf : Final Presentation
- Leads.csv : Data worked on
- Leads Data Dictionary.xlsx : Data Dictionary
- Summary.pdf : Summary on what's done in the entire py file


