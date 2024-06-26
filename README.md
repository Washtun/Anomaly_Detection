# Anomaly_Detection
This notebook covers the techniques for dealing with anomaly detection in financial transaction, along with an example dataset, visuals, and feature selection methods to train and models utilizing these techniques.

 The dataset for the project was downloaded from [statso](https://statso.io/anomaly-detection-case-study). The aim is to develop robust anomaly detection models that can accurately distinguish between normal and abnormal data points, thereby assisting in fraud detection, fault diagnosis, and outlier identification
 
The dataset contains information about various financial transactions, each represented by several features:

Transaction_ID: Unique identifier for each transaction.

Transaction_Amount: The monetary value of the transaction.

Transaction_Volume: The quantity or number of items/actions involved in the transaction.

Average_Transaction_Amount: The historical average transaction amount for the account

Frequency_of_Transactions: How often transactions are typically performed by the account.

Time_Since_Last_Transaction: Time elapsed since the last transaction.

Day_of_Week: The day of the week when the transaction occurred.

Time_of_Day: The time of day when the transaction occurred.

Age: Age of the account holder.

Gender: Gender of the account holder.

Income: Income of the account holder.

Account_Type: Type of account (e.g., Savings, Current).
