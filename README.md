Taiwan Credit Card Default Dataset
Overview
This dataset contains detailed information on credit card clients in Taiwan from April 2005 to September 2005. It includes demographic factors, credit data, repayment history, and bill statements, with the goal of predicting whether a client will default on their next payment.

Dataset Description
The dataset consists of 25 variables describing clients' credit and payment behaviors:

Variable	Description
ID	Client identifier
LIMIT_BAL	Credit limit (NT dollars), including individual and family/supplementary credit
SEX	Gender (1 = male, 2 = female)
EDUCATION	Education level (1, 2, 3, 4, 5, 6)
MARRIAGE	Marital status (1 = married, 2 = single, 3 = others)
AGE	Age in years
PAY_0	Repayment status in September 2005 (scale described below)
PAY_2	Repayment status in August 2005
PAY_3	Repayment status in July 2005
PAY_4	Repayment status in June 2005
PAY_5	Repayment status in May 2005
PAY_6	Repayment status in April 2005
BILL_AMT1	Amount of bill statement in September 2005 (NT dollars)
BILL_AMT2	Amount of bill statement in August 2005
BILL_AMT3	Amount of bill statement in July 2005
BILL_AMT4	Amount of bill statement in June 2005
BILL_AMT5	Amount of bill statement in May 2005
BILL_AMT6	Amount of bill statement in April 2005
PAY_AMT1	Amount of previous payment in September 2005 (NT dollars)
PAY_AMT2	Amount of previous payment in August 2005
PAY_AMT3	Amount of previous payment in July 2005
PAY_AMT4	Amount of previous payment in June 2005
PAY_AMT5	Amount of previous payment in May 2005
PAY_AMT6	Amount of previous payment in April 2005
default.payment.next.month	Default payment status for next month (1 = yes, 0 = no)

Data Preprocessing: Handling missing values and feature scaling for numerical features.

Model Training: Applied classification algorithms such as Logistic Regression, Random Forest, and SVC 

📊 Visualizations
Confusion matrix to assess classification results.

Performance metrics including Accuracy, F1 Score, Recall, and other popular metrics.

 Links
Kaggle Notebook: 

💬 Feedback and Collaboration
I’m always open to feedback and new collaborations! Feel free to connect with me on LinkedIn to share ideas or discuss opportunities.

🌟 My Journey with CodeAlpha
This project is part of my ongoing learning and exploration in AI and machine learning with CodeAlpha. Together, we aim to unlock the power of data-driven insights and build impactful real-world applications.

Looking forward to continuing this exciting journey!
