# Project Description
![image](https://user-images.githubusercontent.com/19640466/141074111-821f917e-6b0c-41d4-9b28-9700542eb221.png)<br>
In order to plan advertising campaigns for the online store Ice, we need to know which game genre and platform is profitable. Given user and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales, we need to identify patterns that determine whether a game succeeds or not.

# Table of Contents:
1. General Information
2. Data preprocessing
   * Replace the column names (make them lowercase).
   * Convert the data to the required types.
   * Describe the columns where the data types have been changed and why.
   * If necessary, decide how to deal with missing values:
       *Explain why you filled in the missing values as you did or why you decided to leave them blank.
       *Why do you think the values are missing? Give possible reasons.
       *Pay attention to the abbreviation TBD (to be determined). Specify how you intend to handle such cases.
   * Calculate the total sales (the sum of sales in all regions) for each game and put these values in a separate column.
3. Data Analysis
   * ex: Look at how many games were released in different years. Is the data for every period significant?
5. Testing the Hypothesis
   —Average user ratings of the Xbox One and PC platforms are the same.
   —Average user ratings for the Action and Sports genres are different.
   Explain:
     * How you formulated the null and alternative hypothesis
     * What significance level you chose to test the hypothesis, and why
6. Conclusion

# **Data**

* *Name*
* *Platform*
* *Year_of_Release*
* *Genre*
* *NA_sales*
* *EU_sales*
* *JP_*
* *Other_sales*
* *Critic_Score*
* *User_Score*
* *Rating*


# **Goal:**
 Identifying trends and patterns to determine which game genres are profitable.

# **Libraries used:**
 *pandas, matplotlib, numpy, scipy, seaborn, math*
