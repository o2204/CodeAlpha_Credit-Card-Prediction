# Taiwan Credit Card Default Dataset

## Overview  
This dataset contains detailed information on credit card clients in Taiwan from April 2005 to September 2005. It includes demographic factors, credit data, repayment history, and bill statements, with the goal of predicting whether a client will default on their next payment.

---

## Dataset Description  
The dataset consists of 25 variables describing clients' credit and payment behaviors:

| Variable                     | Description                                                       |
|------------------------------|-------------------------------------------------------------------|
| **ID**                       | Client identifier                                                 |
| **LIMIT_BAL**                | Credit limit (NT dollars), includes individual and family credit  |
| **SEX**                      | Gender (1 = male, 2 = female)                                    |
| **EDUCATION**                | Education level (1, 2, 3, 4, 5, 6)                              |
| **MARRIAGE**                 | Marital status (1 = married, 2 = single, 3 = others)             |
| **AGE**                      | Age in years                                                     |
| **PAY_0**                    | Repayment status in September 2005 (scale described below)       |
| **PAY_2**                    | Repayment status in August 2005                                  |
| **PAY_3**                    | Repayment status in July 2005                                    |
| **PAY_4**                    | Repayment status in June 2005                                    |
| **PAY_5**                    | Repayment status in May 2005                                     |
| **PAY_6**                    | Repayment status in April 2005                                   |
| **BILL_AMT1**                | Amount of bill statement in September 2005 (NT dollars)          |
| **BILL_AMT2**                | Amount of bill statement in August 2005                          |
| **BILL_AMT3**                | Amount of bill statement in July 2005                            |
| **BILL_AMT4**                | Amount of bill statement in June 2005                            |
| **BILL_AMT5**                | Amount of bill statement in May 2005                             |
| **BILL_AMT6**                | Amount of bill statement in April 2005                           |
| **PAY_AMT1**                 | Amount of previous payment in September 2005 (NT dollars)        |
| **PAY_AMT2**                 | Amount of previous payment in August 2005                        |
| **PAY_AMT3**                 | Amount of previous payment in July 2005                          |
| **PAY_AMT4**                 | Amount of previous payment in June 2005                          |
| **PAY_AMT5**                 | Amount of previous payment in May 2005                           |
| **PAY_AMT6**                 | Amount of previous payment in April 2005                         |
| **default.payment.next.month** | Default payment status for next month (1 = yes, 0 = no)        |

---

## Data Preprocessing  
- Handling missing values.  
- Feature scaling for numerical variables.

---

## Model Training  
- Classification algorithms applied:  
  - Logistic Regression  
  - Random Forest  
  - Support Vector Classifier (SVC)  

---

## 📊 Visualizations  
- Confusion matrix to evaluate classification results.  
- Performance metrics including Accuracy, F1 Score, Recall, and others.

---

## Links  
- **Kaggle Notebook:** [Credit Card Clients](https://www.kaggle.com/code/omaratef200/credit-card-clients)  

---

## 💬 Feedback and Collaboration  
I’m always open to feedback and collaborations! Connect with me on **[LinkedIn](https://www.linkedin.com/in/o2204)** to share ideas or discuss opportunities.

---

## 🌟 My Journey with CodeAlpha  
his project is part of my learning journey with CodeAlpha, where I explore AI and machine learning to create useful real-world solutions.

Looking forward to continuing this exciting journey!

