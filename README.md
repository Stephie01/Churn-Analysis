# SyriaTel Customer Churn Analysis



# 1. PROJECT OVERVIEW

The objective of this project is to build a binary classifier that predicts whether a customer of SyriaTel will churn or not. By identifying potential churners in advance, SyriaTel can take proactive measures to retain customers and minimize revenue loss. This README provides an overview of the project, stakeholders, and the dataset used.

Analysist: Stephanie Mbithe

**Phase 3 project in Moringa School**

### Stakeholder Audience
The stakeholder audience for this project includes:

SyriaTel Management: They are interested in reducing financial losses caused by customer churn and will benefit from insights and strategies to retain customers.

Marketing Department: They can utilize the findings to design targeted retention campaigns and customer loyalty programs.

Customer Service Team: They can prioritize interactions and provide proactive assistance to at-risk customers, improving customer satisfaction and retention.

Sales Team: They can offer personalized offers and incentives to customers identified as being at a higher risk of churning.
Business and Data Understanding.


# 2. Dataset Choice
The chosen dataset contains relevant customer information, usage patterns, and churn status. It includes features such as customer demographics, account details, service plans, usage patterns, and customer service interactions. These features provide valuable insights into customer behavior and can be indicative of churn.

The dataset aligns with the project objective of predicting customer churn for SyriaTel. By analyzing this dataset, we can uncover significant predictors of churn and develop a robust binary classifier and this is a summary;

state: the state the customer lives in
account length: the number of days the customer has had an account
area code: the area code of the customer
phone number: the phone number of the customer
international plan: true if the customer has the international plan, otherwise false
voice mail plan: true if the customer has the voice mail plan, otherwise false
number vmail messages: the number of voicemails the customer has sent
total day minutes: total number of minutes the customer has been in calls during the day
total day calls: total number of calls the user has done during the day
total day charge: total amount of money the customer was charged by the Telecom company for calls during the day
total eve minutes: total number of minutes the customer has been in calls during the evening
total eve calls: total number of calls the customer has done during the evening
total eve charge: total amount of money the customer was charged by the Telecom company for calls during the evening
total night minutes: total number of minutes the customer has been in calls during the night
total night calls: total number of calls the customer has done during the night
total night charge: total amount of money the customer was charged by the Telecom company for calls during the night
total intl minutes: total number of minutes the user has been in international calls
total intl calls: total number of international calls the customer has done
total intl charge: total amount of money the customer was charged by the Telecom company for international calls
customer service calls: number of calls the customer has made to customer service
churn: true if the customer terminated their contract, otherwise false



# 3. MODELLING
The Modelling part entails the following;
1.1 Build Models and Train
1.2 Applying SMOTE Technique to Resolve Unbalanced 'churn' Feature
Model 1 - Logistic Regression Classifier
a.)Hyperparameter Tuning of Logistic Regression Classifier
b) Logistic Regression Models' Comparisons
Model 2 - Random Forest Classifier
a) Hyperparameter Tuning of Random Forest Classifier
b) Random Forest Models' Comparisons
Model 3 - Decision Tree Classifier
a) Hyperparameter Tuning of Decision Tree Classifier
b) Decision Tree Models' Comparisons
Model 4 - K-Nearest Neighbors (KNN)
a) Hyperparameter Tuning of K-Nearest Neighbors (KNN)
b) KNN Models' Comparisons

# 4. EVALUATION
Models Comparison is done in this part using the following techniques;

1.ROC Curve
2. Model Comparisons - F1 Score (10-fold cross-validated)
3. Model Comparisons - Accuracy (10-fold cross-validated)
Applying SFS (Sequential Feature Selector) Feature Selection Techniques

# 5. CONCLUSION

The project concludes with the deployment of the trained model and the establishment of a monitoring mechanism to continuously track customer churn. The README emphasizes the importance of ongoing monitoring, feedback, and iteration to improve the model's performance over time. It also highlights the potential for incorporating additional data sources or features to enhance the model's predictive power.