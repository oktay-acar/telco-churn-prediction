# Telco Churn Prediction

**Business Problem**

It is expected to develop a machine learning model that can predict customers who will leave the company.

Perform the necessary data analysis and feature engineering steps before developing the model.

**Dataset Story**

**Telco** churn data includes information about a fictitious telecom company that provided home phone and internet services to 7.043 California customers in the third quarter. It shows which customers have left, stayed or signed up for their service.

**Variables**
- **CustomerId:** Customer ID
- **Gender:** Gender
- **SeniorCitizen:** Whether the client is older *(1, 0)*
- **Partner:** Whether the client has a partner *(Yes, No)*? Married or not
- **Dependents:** Whether the customer has dependents *(Yes, No) (Child, mother, father, grandmother)*
- **tenure:** The number of months the customer has stayed with the company
- **PhoneService:** Whether the customer has phone service *(Yes, No)*
- **MultipleLines:** Whether the customer has more than one line *(Yes, No, No Telephone service)*
- **InternetService:** Customer's internet service provider *(DSL, Fiber optic, No)*
- **OnlineSecurity:** Whether the customer has online security *(Yes, No, No Internet service)*
- **OnlineBackup:** Whether the customer has an online backup *(Yes, No, No Internet service)*
- **DeviceProtection:** Whether the customer has device protection *(Yes, No, No Internet service)*
- **TechSupport:** Whether the customer has technical support *(Yes, No, No Internet service)*
- **StreamingTV:** Whether the customer is broadcasting TV *(Yes, No, No Internet service)*. Indicates whether the customer uses the Internet service to stream television programs from a third-party provider
- **StreamingMovies:** Whether the customer is streaming movies *(Yes, No, No Internet service)*. Indicates whether the customer is using Internet service to stream movies from a third-party provider
- **Contract:** Customer's contract duration *(Month to month, One year, Two years)*
- **PaperlessBilling:** Whether the customer has a paperless invoice *(Yes, No)*
- **PaymentMethod:** Customer's payment method *(Electronic check, Postal check, Bank transfer (automatic), Credit card (automatic))*
- **MonthlyCharges:** The amount charged to the customer monthly
- **TotalCharges:** The total amount charged from the customer
- **Churn:** Whether the customer used *(Yes or No)*. Customers who left in the last month or quarter

**:memo: Notes**
- Each row represents a unique customer.
- Variables include information about customer service, account, and demographics.
  - **Services customers sign up for:** Phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies.
  - **Customer account information:** How long they have been a customer, contract, payment method, paperless billing, monthly fees, and total fees.
  - **Demographic information about customers:** Gender, age range, and whether they have partners and dependents.

---

## Requirements
~~~python
catboost==1.2
lightgbm==3.3.5
matplotlib==3.7.1
numpy==1.24.3
pandas==1.5.1
seaborn==0.12.1
sklearn==1.3.1
xgboost==1.7.5
~~~

---

## Author
[Oktay Acar](https://github.com/oktay-acar)