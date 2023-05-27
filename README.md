# Bank Term Deposit Prediction
![Vadeli_Altin_Mevduat_Hesabi](https://github.com/ecemolgun/Bank-term-deposit-prediction/assets/79108733/05c80f4f-89f0-45ea-bb9c-5c7c95d1d67c)
# Business Problem 🖇️ 📝

The project aims to develop a model that can predict the probability of customers opening a deposit account. In this way, it aims to create effective marketing campaigns for customers who are likely to open a potential deposit account.

The results obtained in this project showed great potential in the field of data analytics and machine learning and I hope it can make a great contribution in increasing the effectiveness of future marketing strategies.

## Variables 🎯

1 - Age (numeric)

2 - Job : type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')

3 - Marital : marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)

4 - Education (categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate','professional.course','university.degree','unknown')

5 - Default: has credit in default? (categorical: 'no','yes','unknown')

6 - Housing: has housing loan? (categorical: 'no','yes','unknown')

7 - Loan: has personal loan? (categorical: 'no','yes','unknown')

8 - Contact: contact communication type (categorical: 'cellular','telephone')

9 - Month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')

10 - Day_of_week: last contact day of the week (categorical: 'mon','tue','wed','thu','fri')

### Other Attributes:

11 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

12 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

13 - previous: number of contacts performed before this campaign and for this client (numeric)

## Base Model 🔍

By using the Voting Classifier method in the modeling phase; Random Forest, KNN, and LightGBM algorithms were used for calculating F1 and Accuracy scores. 
