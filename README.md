# EDA-on-Telecom-Customer-Churn
This project performs an exploratory data analysis (EDA) on the Telecom Customer Churn dataset to understand patterns behind customer churn.

📊 Dataset
The dataset provides a comprehensive view of telecom customers, including their demographics, account information, and the services they've subscribed to. It contains 7043 rows and 21 columns.

Column Description 
- customerID – Unique identifier assigned to each customer.
- gender – Customer’s gender (Male/Female).
- SeniorCitizen – Indicates if the customer is a senior citizen (1 = Yes, 0 = No).
- Partner – Whether the customer has a spouse/partner (Yes/No).
- Dependents – Whether the customer has dependents (children or others) (Yes/No).
- tenure – Number of months the customer has stayed with the company.
- PhoneService – Whether the customer has a phone service (Yes/No).
- MultipleLines – If the customer has multiple phone lines (No phone service/No/Yes).
- InternetService – Type of internet service (DSL/Fiber optic/No).
- OnlineSecurity – Whether the customer has online security add-on (Yes/No/No internet service).
- OnlineBackup – Whether the customer has online backup add-on (Yes/No/No internet service).
- DeviceProtection – Whether the customer has device protection plan (Yes/No/No internet service).
- TechSupport – Whether the customer has technical support add-on (Yes/No/No internet service).
- StreamingTV – Whether the customer has streaming TV service (Yes/No/No internet service).
- StreamingMovies – Whether the customer has streaming movies service (Yes/No/No internet service).
- Contract – Customer’s contract type (Month-to-month/One year/Two year).
- PaperlessBilling – Whether the customer opts for paperless billing (Yes/No).
- PaymentMethod – Method used by customer to pay (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).
- MonthlyCharges – Amount charged to the customer every month.
- TotalCharges – Total amount charged to the customer over the entire tenure.
- Churn – Target variable: whether the customer left the service (Yes = churned, No = retained).

📊 Questions Explored Through Plots

What is the count of customers who churned vs. stayed?

What is the percentage of churned vs. retained customers?

Does gender affect churn?

What is the distribution of customers by senior citizen status?

Do senior citizens churn more than non-senior citizens?

How does customer tenure influence churn?

How does contract type impact churn?

Does payment method affect churn?
