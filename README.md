# Credit-Card-Fraud-Detection


## Project Overview

○ This project aims to build a Machine learning model that can recognize fraudulent transaction . 

○ The dataset contains various features such as :
	
[Transaction ID] - Does not contribiute in determining the target column i.e Fraud . However it will be use if we want to notify the 
device where this type of transaction is taking place .

[Date,Day of Week,Time] - May be important as this type of data is time series .

○ Categorical Columns : 
These columns need to be converted to numerical format by using one hot encoding . 

[Type of Card , Entry Mode	,Amount	,Type of Transaction,	Merchant Group,	Country of Transaction,	Shipping Address,	Country of Residence,	Gender	,Age,Bank]
   
[Fraud]  - The final target column which has  to be  predicted . 


## Objectives

○ Dropping the unnecessary columns -[Transaction_id]

○ Checking for null values . As their are very few null values in comparision to the dataset ,the most optimal way is to drop the rows with null values.

○ Checking for categorical column and then converting them to numerical one using one hot encodiong . 

○ Converting date column to datetime datatype

○ Converting amount column to numerical

○ Visualising dataset by correlation with target column

○ Checking for dataimbalance , applying SMOTE for dataimbalance. 

○ Training the model using xgboost . 





## Technologies Used

○ Python: The core programming language for implementing the data processing and web application.

○ Pandas : For data manipulation and analysis.

○ XGBoost: For training the model.

○ SMOTE - For balancing the imbalance dataset .

○ Sklearn - For applying One Hot Enoding to categorical columns.

○ Seaborn and matplot - For visualizing the heatmap for varius columns with target column. 
