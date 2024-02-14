# Python_Marketing_Campaign_Analytics
1. Objective:
The project is to leverage the dataset sourced from kaggle, describing the marketing efforts focused through direct phone calls by a banking institution. the aim of the project is to enhancing marketing campaign efficiency by using data-driven strategies.

The data compromises of 21 features related to customer, product, and social-economic attributes, columns are described as follow:
(1)	Demographic Data: including client age, job, marital, education, default on whether they have credit, housing, and loan.
(2)	Last Contact Data: including contact time, month, day of week, duration.
(3)	Campaign Data: campaign, days since the client was last contacted in a previous campaign, count of contacts before the current campaign for the client and outcome of the previous marketing campaign.
(4)	Socio-economic Indicators: employment variation rate, consumer price index, consumer confidence index, Canadian Overnight Repo Rate average 3-month rate and number of employees
(5)	Target data: subscribed (binary outcome: yes or no), indicates whether the client subscribed to a term deposit post in the campaign.

2. Methodology:
1) Cluster analysis: Cluster analysis identified three distinct customer segments, with the Millennial Cluster showing the highest subscription willingness.
2) Machine learning predictions: predict if targeted customers will opt for a fixed-term deposit after a marketing campaign. the following models are tried: Random Forest, Decision Tree,
   LightGBM, KNN, logistic regression, Bagging, XGBoost initially.
A Random Forest model was selected for targeting this cluster, achieving a recall of 80% and precision of 47%. Recommendations include optimizing marketing strategies based on these insights to improve campaign efficiency and ROI, with a particular focus on mobile engagement and targeted outreach.
3) Analytical modelling process: 
1.	Define the marketing analytics problem statement.
2.	Data exploration: identified Kaggle dataset. 
3.	Data preparation
a.	Cleaning (outliers, missing values, data types, inconsistencies)
b.	Feature engineering (normalization, discretization, coding, hyperparameter tuning)
c.	Feature selection 
d.	Split the data.
4.	Cluster Analysis (cluster/segment the customer throught customer subscriptions or their spending behavior, and understand the targeted customers and factors that influence the likelihood of subscription) 
5.	Classification Modeling (Train classification algorithms (e.g., Logistic Regression, Random Forest, Support Vector Machines etc.) to predict whether a client will subscribe. 
6.	Evaluation (Evaluate their performance using appropriate metrics (e.g., accuracy, precision, recall, F1-score).
7.	Deployment 
8.	Monitoring and Iteration

Data Source

https://www.kaggle.com/datasets/berkayalan/bank-marketing-data-set


