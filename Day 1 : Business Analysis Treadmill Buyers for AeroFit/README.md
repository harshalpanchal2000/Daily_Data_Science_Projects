# **Project Showcase: AeroFit Treadmill Customer Profiling**

## Problem Statement:
The market research team at AeroFit aims to identify the characteristics of the target audience for each type of treadmill offered by the company. The goal is to provide better recommendations of treadmills to new customers by investigating differences across products with respect to customer characteristics.

## Solution: 
  ### Data Preprocessing:
  - The dataset contains 180 entries with no null values.
  - Two features, 'Gender' and 'MaritalStatus', were one-hot encoded to convert them into numerical values.
  - 'Product' feature was label-encoded to map product identifiers to categories.
  - Unnecessary columns like 'Gender_Female' and 'MaritalStatus_Single' were dropped.
  - The dataset was split into subdatasets for each treadmill product.
  
  ### Descriptive Analytics:
  1. **Overall Customer Distribution:**
     - Bar charts were created to visualize the distribution of 'Gender', 'MaritalStatus', and 'Product' across all customers.
     - Insights: The majority of customers are male, and most of them are partnered. The best-selling product is KP281.
  
  2. **Product-specific Analysis:**
     - Separate profiles were created for Entry Level, Mid Level, and Advanced Level Treadmills.
     - Insight: Entry Level Treadmills (80 units) outsell Advanced Level Treadmills (40 units) by a significant margin.
  
  ### Statistical Analysis:
  1. **Basic Exploratory Data Analysis (EDA):**
     - Shape, information, and basic statistics of the dataset were provided.
     - Insight: The dataset has 180 entries with numerical and categorical features.
  
  2. **Univariate Analysis: Numerical Variables:**
     - Distance plots and count plots were created for numerical variables like 'Age', 'Education', 'Usage', 'Fitness', 'Income', and 'Miles'.
     - Observation: Fitness level '3' customers are the majority buyers, and customers aged 23-28 are the primary audience.
  
  3. **Univariate Analysis: Categorical Variables:**
     - Count plots were generated for categorical variables like 'Product', 'Gender', and 'MaritalStatus'.
     - Observation: KP281 is the most frequent and best-selling product.
  
  4. **Bivariate Analysis:**
     - Bar charts were created to analyze the relationship between 'Product' and 'Gender', 'MaritalStatus', and 'Age'.
     - Observation: Males and Females show similar purchasing patterns for KP281, while KP781 is preferred by more male customers.
  
  5. **Box Plots:**
     - Box plots were used to identify outliers and distributions for numerical variables.
     - Observation: 'Income' and 'Miles' have significant outliers.
  
  ### Insights and Recommendations:
  1. **Sales Overview:**
     - Entry Level Treadmills (KP281) dominate sales, making up twice the sales of Advanced Level Treadmills (KP781).
  
  2. **Customer Profile:**
     - Majority of customers are male, partnered, and aged 23-28.
     - Fitness level '3' customers are the primary buyers.
  
  3. **Product-specific Recommendations:**
     - Focus marketing efforts on KP281 for a wider audience.
     - Explore opportunities to promote KP781 among fitness-focused male customers.
  
  4. **Potential Improvements:**
     - Address outliers in 'Income' and 'Miles' for a more accurate customer profile.
     - Conduct further surveys to understand customer preferences and improve product offerings.
  
  ### Conclusion:
  The analysis provides valuable insights into customer characteristics and purchasing patterns for AeroFit's treadmill products. This information can guide marketing strategies, product development, and customer targeting for better business outcomes.
  
### Further Analysis:
Continued analysis will include addressing outliers, conducting customer surveys, and refining recommendations for a more comprehensive understanding of customer preferences and market dynamics.
