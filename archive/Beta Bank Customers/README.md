# Project Description
![image](https://user-images.githubusercontent.com/19640466/141059133-da9adfa8-8763-4a7c-b7d6-864be8cefd39.png)<br>
Beta Bank customers are leaving little by little, chipping away every month. Given data on client's past behavior and termination of contracts with the bank, we have to predict whether a customer will leave the bank soon.
# Table of Contents
1. General information about dataset
2. Data Preprocessing
3. Splitting data into test/train/validation set
4. Improving model quality

# Data:
**Features**
* *RowNumber* — data string index
* *CustomerId* — unique customer identifier
* *Surname* — surname
* *CreditScore* — credit score
* *Geography* — country of residence
* *Gender* — gender
* *Age* — age
* *Tenure* — period of maturation for a customer’s fixed deposit (years)
* *Balance* — account balance
* *NumOfProducts* — number of banking products used by the customer
* *HasCrCard* — customer has a credit card
* *IsActiveMember* — customer’s activeness
* *EstimatedSalary* — estimated salary

**Target**
* *Exited* — Customer has left the bank

**Goal:**
To predict whether a customer will leave the bank, build a model with the maximum possible F1 score.

**Libraries used:**<br>
*pandas, sklearn.ensemble, sklearn.linear_model, sklearn.tree, sklearn.model_selection, sklearn.metrics, sklearn.preprocessing, numpy*
