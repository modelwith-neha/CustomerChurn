Used https://www.kaggle.com/datasets/blastchar/telco-customer-churn - Telco Customer Churn Dataset from Kaggle 
To harness predictive modeling to extract meaningful insights from data using models like Naïve Bayes, Decision Tree, Random Forest, KNN and also dwelve into feature importance 
and conditional probability.
Key Features- Demographics: Age of the customer.
              Subscription Details: Subscription length, contract type (one-year, two-year, month-to-month).
              Usage Behavior: Total data usage (GB), number of support calls.
              Billing & Payment: Payment method, additional services subscribed.
Objective- Use machine learning for binary classification to predict churn and thus help businesses identify at-risk customers and reduce churn.
On preprocessed data, this is the final outcome- 
          Accuracy: Random Forest achieved the highest accuracy, outperforming other models.
          ﻿﻿Precision & Recall: Trade-off observed: Decision Trees had high precision but lower recall, while KNN struggled with both.
          ﻿﻿F1-Score:  Random Forest maintained the best balance.
          ﻿﻿Class Imbalance: Some models were impacted by imbalanced data, affecting recall and precision. So applied SMOTE beforehand.
