# E-commerce-Customer-Behavior-SPSS-PROJECT
# Overview
This project explores the E-commerce Customer Behaviour Dataset provided by [Kaggle](https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset). This dataset provides a comprehensive view of customer behaviour within an e-commerce platform. Each entry in the dataset corresponds to a unique customer, offering a detailed breakdown of their interactions and transactions. The information is crafted to facilitate a nuanced analysis of customer preferences, engagement patterns, and satisfaction levels, aiding businesses in making data-driven decisions to enhance the customer experience. <br />
The transformed dataset and the raw SPSS output file are presented above along with the results and discussions in a Word document presented in APA 7th edition format which goes in-depth into the findings. Below is a quick summary of findings and recommendations based on the results obtained from the dataset.<br />

# Data Preparation
The variables Age, Gender, Membership Type, Satisfaction level and Discount Applied were recoded into different variables. <br />
The descriptive statistics option was used to check for missing values in the dataset. The variable "Satisfaction level" had 2 missing cases, so the records on the 2 individuals bearing the missing values were removed thus reducing the total number of records in the dataset from 350 to 348. Furthermore, the variable Total Spent was not normally distributed so, a box-cox transformation was done to achieve normality.

# Objectives
Objective 1: Descriptive statistics for Age, Membership Type, and Satisfaction Level. This was achieved using frequency count, mean, and percentages. <br />

Objective 2: Customer Segmentation (Cluster Analysis). This involved the use of hierarchical cluster analysis and K-Means Cluster Analysis. Hierarchical cluster analysis was carried out to obtain the number of clusters that would be used for the K-Means Cluster Analysis. <br />

Objective 3: Relationship Between Demographics and Spending (Chi-Square Test for Association). This was achieved using a chi-square test to examine if there is a significant relationship between gender and membership type. <br />

Objective 4: Analysis of Variance (ANOVA) between variables total spent and age category. <br />

Objective 5: Customer Satisfaction Analysis (Chi-Square Test for Association). This involved using a chi-square test to examine if there is a significant relationship between satisfaction level and membership type. <br />

Objective 6: Effect of Discounts on Purchase Behaviour (t-test ) This was achieved using a t-test to compare the average total spent between customers who received a discount versus those who did not. <br />

Objective 7: Retention Analysis (Correlations). This was achieved using correlation analysis to study the relationship between the days since the last purchase, satisfaction level and membership type.

# Tools I Used
* IBM SPSS 26
* Microsoft Word <br />

# Hypothesis Testing
* Is there a significant association between gender and membership type? <br />
  H<sub>0</sub>: There is no significant difference between gender and membership type. <br />
  H<sub>1</sub>: There is a significant difference between gender and membership type. <br />
  
* Is there a significant difference in the means for total spending and age category? <br />
  H<sub>0</sub>: The means are equal for total spend and age category.  <br />
  H<sub>1</sub>: The means are different for total spending and age category.  <br />

* Is there a significant difference between satisfaction level and membership type? <br />
  H<sub>0</sub>: There is no significant difference between satisfaction level and membership type. <br />
  H<sub>1</sub>: There is a significant difference between satisfaction level and membership type. <br />

* Is there a significant difference between total spending and discount applied? <br />
   H<sub>0</sub>: There is no significant difference between total spend and discount applied.
   H<sub>1</sub>: There is a significant difference between total spend and discount applied. <br />

* Is there a significant relationship between days since the last purchase, membership type, and satisfaction level? <br />
   H<sub>0</sub>: No significant relationships between days since the last purchase, membership type, and satisfaction level. <br />
   H<sub>1</sub>: Significant relationships between days since last purchase, membership type, and satisfaction level. <br />

# Insights
Objective 1: From the descriptive statistics, Of the 348 samples, 49.7% of the customers were of the age range 31-39, and there were a close number of males and females (50.3%) and (49.7%) respectively, bronze, silver, and gold membership subscribers were split evenly(32.8%) (33.6%) and (33.6%) respectively. The majority of the customers were satisfied (35.9%) <br />

Objective 2: Four customer clusters were identified based on age, items purchased, and total spending:
* Cluster 1: Older customers (avg. age 32) with low spending.
* Cluster 2: Oldest customers (avg. age 39) with the lowest spend.
* Cluster 3: Slightly younger customers (avg. age 31) with moderate spending.
* Cluster 4: Youngest customers (avg. age 29) with the highest spend.
Younger customers tend to spend more, therefore, targeted promotions should focus on this high-spending group (Clusters 3 and 4). For older customers (Clusters 1 and 2), marketing strategies should be developed to encourage more spending and larger purchases. accordingly​ <br />

Objective 3: A significant relationship was found between gender and membership type. Female customers are more likely to have Bronze memberships, while males are more likely to have Gold memberships​. The company should focus on designing gender-specific membership upgrade strategies <br />

Objective 4: Younger customers (under 30) tend to spend more than older ones. Marketing strategies such as loyalty programs and exclusive discounts could help retain these high-spending younger customers, while additional incentives may be needed to encourage spending in the older groups. <br />

Objective 5: Gold members are more likely to report satisfaction, while Bronze and Silver members report lower satisfaction levels. The company should consider enhancing the experience for Bronze and Silver members to improve satisfaction and retention. <br />

Objective 6: Customers who did not receive a discount spent significantly more ($909.01) compared to those who did receive a discount ($787.27). Indicating that discounts may be attracting more price-sensitive customers. Future promotions could focus on maintaining customer engagement after the discount period ends. <br />

Objective 7: A negative correlation was found between days since the last purchase and membership type and a positive correlation between days since the last purchase and satisfaction level. Therefore, maintaining engagement through frequent touchpoints and personalized offers could enhance customer satisfaction. <br />

# Hypothesis Test Results
 * Is there a significant association between gender and membership type? <br />
  Based on the chi-square test, we reject the null hypothesis and conclude that there was a significant association between gender and membership type <br />

* Is there a significant difference in the means for total spending and age category?
  From the ANOVA result, we reject the null hypothesis and conclude that the means for total spending and age category were different. <br />
  
* Is there a significant association between satisfaction level and membership type?
  We reject the null hypothesis and conclude that there was a significant association between satisfaction level and membership type. <br />
  
* Is there a significant difference between the total spent and discount applied?
  The null hypothesis was rejected based on the t-test result, indicating that there was a significant difference between total spending and the discount applied. <br />
  
* Is there a significant relationship between days since the last purchase, membership type, and satisfaction level?
  From the correlation analysis, we reject the null hypothesis and conclude that there was a significant relationship between days since the last purchase, membership type, and satisfaction level.
