# Telco Churn Prediction with Machine Learning
![TelcoChurn](https://user-images.githubusercontent.com/84645968/217059544-0e4bf3e3-b5b3-4f37-a108-8ccd7573810e.png)
## Business Problem
It is expected to develop a machine learning model that can predict customers who will leave the company.
## Dataset
Telco churn data includes information about a fictitious telecom company that provided home phone and Internet services to 7,043 California customers in the third quarter. It shows which customers have left, stayed or signed up for their service.

21 Features 7043 Observations 977.5 KB

| Feature | Definition |
| --- | --- |
| CustomerId | Customer Id |
| Gender | Whether the customer is a male or a female |
| SeniorCitizen | Whether the customer is a senior citizen or not (1, 0) |
| Partner | Whether the customer has a partner or not (Yes, No) |
| Dependents | Whether the customer has dependents or not (Yes, No) |
| tenure | Number of months the customer has stayed with the company |
| PhoneService | Whether the customer has telephone service or not (Yes, No) |
| MultipleLines | Whether the customer has more than one line or not (Yes, No, No phone service) |
| InternetService | Customer's internet service provider (DSL, Fiber optic, No) |
| OnlineSecurity | Whether the customer has online security or not (Yes, No, no Internet service) |
| OnlineBackup | Whether the customer has an online backup or not (Yes, No, no Internet service) |
| DeviceProtection | Whether the customer has device protection or not (Yes, No, no Internet service) |
| TechSupport | Whether the customer has technical support or not (Yes, No, no Internet service) |
| StreamingTV | Whether the customer has a TV broadcast or not (Yes, No, no Internet service) |
| StreamingMovies | Whether the client has streaming movies or not (Yes, No, no Internet service) |
| Contract | The contract term of the customer (Month to month, One year, Two years) |
| PaperlessBilling | Whether the customer has a paperless invoice or not (Yes, No) |
| PaymentMethod | Customer's payment method (Electronic check, Postal check, Bank transfer (automatic), Credit card (automatic)) |
| MonthlyCharges  | Amount collected from the customer on a monthly basis |
| TotalCharges | Total amount charged from customer |
| Churn | Whether the customer churned or not (Yes or No) |
## Requirements
```
catboost==1.1.1
lightgbm==3.2.1
matplotlib==3.4.3
numpy==1.20.3
pandas==1.3.4
seaborn==0.11.2
session_info==1.0.0
sklearn==0.24.2
xgboost==1.7.3
```
## Author
[Çağla Deniz Doruk](https://github.com/cagladenizdoruk)
