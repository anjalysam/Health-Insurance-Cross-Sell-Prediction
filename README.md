# Health-Insurance-Cross-Sell-Prediction
Predict Health Insurance Owners' who will be interested in Vehicle Insurance
# Problem Statement 
Your client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the customers from past year will also be interested in Vehicle Insurance provided by the company.
# Business Goal
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

# Data Discription
Data Source : Kaggle

Data Source Link : https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction?select=train.csv

The Dataset used for the analysis includes the following columns:

id : Unique ID for the customer

Gender : Gender of the customer

Age : Age of the customer

Driving_License : 0 - Customer does not have DL,1 - Customer already has DL

Region_Code : Unique code for the region of the customer

Previously_Insured : 1 - Customer already has Vehicle Insurance, 0-Customer doesn't have Vehicle Insurance

Vehicle_Age : Age of the Vehicle Vehicle_Damage : 1 - Customer got his/her vehicle damaged in the past. 0 -Customer didn't get his/her vehicle damaged in the past.

Annual_Premium : The amount customer needs to pay as premium in the year

PolicySalesChannel : Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

Vintage : Number of Days, Customer has been associated with the company

Response : 1 - Customer is interested, 0 - Customer is not interested

# Conclusion
The ML model for the problem statement was created using python with the help of the dataset, and the ML model created with Random Forest and XGBClassifier models performed better than Logistics Regression model. Thus, for the given problem, the models created by Random Forest and XGBClassifier.
