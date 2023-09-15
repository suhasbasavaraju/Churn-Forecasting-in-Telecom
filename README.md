# Telecom-High-Risk-Churn-Prediction

This GitHub repository is dedicated to a comprehensive case study in the telecom industry, focused on analyzing customer-level data. The primary objective is to construct predictive models that effectively identify customers at high risk of churn. Additionally, this project aims to discern the key indicators and patterns associated with churn within this competitive sector.

### Workflow Highlights

1. Data Exploration and Understanding: Comprehensive examination of the dataset to grasp its intricacies.

2. Data Cleaning: Rigorous data cleansing procedures to ensure data quality and reliability.

3. Feature Engineering: Crafting relevant features to enhance model performance.

4. Data Preparation: Structuring and preprocessing the data for predictive modeling.

5. Model Development and Evaluation: Building predictive models and assessing their effectiveness.

6. Final Model Selection: Determining the most suitable model for churn prediction.

### Top Predictive Features

The following features have been identified as significant predictors of churn:

1. loc_ic_mou_8
2. gd_ph_loc_ic_mou
3. last_day_rch_amt_8
4. total_rech_num_8
5. spl_ic_mou_8
6. monthly_3g_8
7. aon
8. monthly_2g_8
9. sachet_2g_8
10. vbc_3g_8


### Key Insights
-> Most of the top predictors are derived from month 8, a critical action phase where customer interactions become pivotal, emphasizing the importance of focusing on this period.

-> Churners tend to have significantly lower network usage during the action phase, directly impacting the company's revenue.

-> Churners are less likely to utilize volume-based cost services, leading to a lower mean value for this group.

-> Surprisingly, users with minimal VBC data usage but high revenue generation exhibit a higher churn rate.

-> Customers who perform high-value recharges tend to use the service for local purposes less frequently compared to those with lower recharge amounts.

-> Individuals with low max recharge amounts and limited local outgoing activity during the "good" phase are more prone to churn.

-> These insights provide valuable guidance for telecom companies to devise targeted retention strategies and mitigate churn among their customer base effectively.





