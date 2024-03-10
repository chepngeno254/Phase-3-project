Title: Prediction of customer churn: SyriaTel Telecommunications

Table of contents
1. Overview
2. Business and data understanding
3. Modelling 
4. Evaluation
7. Conclusion

Overview:

SyriaTel, a telecommunications company, faces a significant challenge in reducing customer churn, which can negatively impact their revenue and profitability. Customer churn refers to the phenomenon where customers discontinue their services with a company, often switching to competitors or simply discontinuing the service altogether. The percentage rate of customer churn in the comapany is approximately 15%. some of the factors contributing significantly to customer churn are Poor service experience and customer service, making it easy for customers to switch providers and poor customer experiences, such as multiple contacts for issue resolution. These factors highlight the importance of addressing service quality and customer satisfaction to reduce churn rate.

Business and data understanding:

The stakeholders are senior management, markerting and customer service team. Predicting customer churn is essential for SyriaTel to retain its customer base and minimize revenue loss. By identifying customers at risk of churning, SyriaTel can proactively engage with them through incentives, personalized offers, or enhanced customer service. The high cost of acquiring new customers compared to retaining existing ones motivates companies like SyriaTel to focus on churn reduction strategies. Leveraging predictive modelling allows for the detection of behavioural patterns indicating a high likelihood of churn. This proactive approach aims to enhance customer retention rates and overall business performance

The dataset consist of 3333 rows and 21 columns. The column include a mix of data types that is object, integer, float and boolean. There are no missing values and duplicates. The columns for the dataset are as follows:
“state', 'account length', 'area code', 'phone number',  'international plan', 'voice mail plan', 'number voicemail messages',  'total day minutes', 'total day calls', 'total day charge',  'total eve minutes', 'total eve calls', 'total eve charge',  'total night minutes', 'total night calls', 'total night charge',  'total international minutes', 'total intl calls', 'total international charge',  'customer service calls', 'churn'

Modelling:

The modelling techniques were:
1. Logistic regression model (baseline model)
2. Decision trees model
3. K-Nearest Neighbor model (KNN)
4. Random Forest model
5. Gradient Boosting model


Evaluation:

The metrics utilized to evaluate performance were Accuracy, precision and  Receiver Operating Characteristic Area Under the Curve(ROC AUC) score. Gradient Boosting model consistently outperforms the other models on both the training and test sets, achieving the highest accuracy, precision, and ROC AUC score. Therefore, the Gradient Boosting model is deemed the best among the five models considered for this classification task.
The advantages of Gradient model are high accuracy, robustness to overfitting, handling Non-linear relationships and can handle various types of data numerical and categorical features.

Conclusion:

The gradient boosting model, after thorough evaluation and validation, emerged as the most effective predictive model for identifying customer churn in the SyriaTel telecommunications company dataset. Its high accuracy and robustness make it a valuable tool for informing strategic decisions and implementing retention strategies to reduce customer churn and improve business outcomes.
The 510 area code had the highest percentage rate of 14.88%, the 408 area code had a rate of 14.56%, and the 415 area code had a rate of 14.26%.
Feature importance analysis provided insights into the factors contributing to customer churn, allowing for targeted interventions
The most influential factors to customer churn include the total minutes spent on day calls, the frequency of customer service calls, the charges associated with day calls, the presence of international plans, and the charges for international calls.

The graph below illustrate the percentage rate of customer churn per area state:-
<img width="529" alt="image" src="https://github.com/chepngeno254/Phase-3-project/assets/151640004/1871e761-c728-49b1-9a1f-022fc7986f9f">

Links:

CustomerChurn_Notebook: https://drive.google.com/file/d/1CkQxpuSDovKwQFmYVUS5Vr4ATL46YOeJ/view?usp=sharing

CustomerChurn_Presentantion: https://drive.google.com/file/d/1HDkxUFQVUXz0d4ZpWmPb2xF-COcBp6vR/view?usp=sharing







