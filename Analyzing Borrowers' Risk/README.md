# **Project Description**
![image](https://user-images.githubusercontent.com/19640466/141062829-2d328c2f-ff4a-479c-9c99-dcdea4ea4fcd.png)
Given data on customer's credit worthiness, we will determine if a customer's marital status and number of children have an impact on whether they will default on a loan. After, we will prepare a report with our results.

# **Table of Contents:**
1. General information about the data set
2. Data Preprocessing
   * Identify and fill in missing values
   * Replace the real number data type with the integer type
   * Delete duplicate data
   * Categorize the data

   Be sure to explain:
     * Which missing values you identified
     * Possible reasons these missing values were present
     * Which method you used to fill in missing values
     * Which method you used to find and delete duplicate data and why
     * Possible reasons why duplicate data was present
     * Which method you used to change the data type and why
     * Which dictionaries you've selected for this dataset and why

The data may contain artifacts, or values that don't correspond to reality (for instance, a negative number of days employed). This kind of thing happens when you're working with real data. We need to describe the possible reasons such data may have turned up and process it.

3. At the end, we will answer these questions:
   * Is there a connection between having kids and repaying a loan on time?
   * Is there a connection between marital status and repaying a loan on time?
   * Is there a connection between income level and repaying a loan on time?
   * How do different loan purposes affect on-time loan repayment?

4. General Conclusion

# **Data**

* *children* — the number of children in the family
* *days_employed* — how long the customer has been working
* *dob_years* — the customer’s age
* *education* — the customer’s education level
* *education_id* — identifier for the customer’s education
* *family_status* — the customer’s marital status
* *family_status_id*— identifier for the customer’s marital status
* *gender* — the customer’s gender
* *income_type* — the customer’s income type
* *debt* —whether the customer has ever defaulted on a loan
* *total_income* — monthly income
* *purpose* — reason for taking out a loan

# **Goal:**
To use data preprocessing to understand the data set and find indications that a beta bank customer will leave. 

# **Libraries used:**
 *pandas*, *matplotlib*, *numpy*
