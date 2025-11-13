Predictive Modeling for Click Through Rate Optimization at ConnectSphere Digital
Prepared By: Yash Mhaske

1.Introduction
This project focuses on predicting whether a user will click on an online advertisement using logistic regression. The aim is to optimize ad targeting and improve the click-through rate (CTR) for digital marketing campaigns.


2. Problem Statement
ConnectSphere Digital faces inefficient ad spend due to displaying ads to users with low engagement probability. The goal is to build a predictive model that classifies users as likely or unlikely to click.


3. Dataset Description
The dataset contains user information such as Daily Time Spent on Site, Age, Area Income, and Daily Internet Usage. The target variable is whether the user clicked on the ad (1) or not (0).


4. Methodology
We used Logistic Regression, a supervised machine learning algorithm for binary classification, to predict user click behavior. The dataset was split into training (70%) and testing (30%) sets. The model was evaluated using accuracy, precision, recall, and F1-score.


5. Model Evaluation 
Accuracy of Model: 92%


6.Classification Report
0:Precision=0.89, Recall=0.95, F1-Score=0.92
1:Precision=0.95, Recall=0.88, F1-Score=0.91
Macro-avg: Precision=0.92, Recall=0.91, F1-Score=0.92
Weighted-avg: Precision=0.92, Recall=0.92, F1-Score=0.92


6. Results and Insights 
The model achieved a high accuracy, demonstrating strong ability to distinguish between users likely and unlikely to click. Age and daily internet usage were significant predictors. 


7. Business Impact 
Integrating this model enables ConnectSphere Digital to allocate ad budgets more efficiently by targeting high-probability users. This increases CTR and overall return on ad spend (ROAS)


8. Conclusion and Future Scope 

The logistic regression model effectively predicts ad click likelihood. Future work can involve testing advanced models like Random Forests or XGBoost, and integrating real-time prediction into ad platforms.
