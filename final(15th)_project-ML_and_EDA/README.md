# Final Project for Practicum Bootcamp
## Exploratory Data Analysis and Machine Learning Model to Predict Churn of Clients for a Telecom Operator
### Description:
The telecom operator Interconnect would like to be able to forecast their churn of clients. If it's discovered that a user is planning to leave, they will be offered promotional codes and special plan options. We are provided with some of their clientele's personal data, including information about their plans and contracts. The target feature is in the `'EndDate'` column where it equals `'No'`. This project consists of data preprocessing, exploratory data analysis, data preparation for training, evaluation and training of different machine learning models to predict termination of contract, and selection of best model. The primary metric is AUC-ROC and additional metric used is Accuracy.

### Data:
The data consists of files obtained from different sources:

- `contract.csv` — contract information.
  - *customerID* - unique code assigned to each client.
  - *BeginDate* - date the contract started.
  - *EndDate* - date the contract has been terminated, 'no' otherwise.
  - *Type* - whether it is a monthly payment or 1- or 2-year contract.
  - *PaperlessBilling* - whether the bills are paperless.
  - *PaymentMethod* - payment method chosen by the customer : bank transfer (automatic), credit card (automatic), electronic check, or mailed check.   
  - *MonthlyCharges* - the monthly charge.
  - *TotalCharges* - the total paid over the duration of the contract.
- `personal.csv` — the client's personal data
  - *customerID* - unique code assigned to each client.
  - *gender* - The customer's gender.
  - *SeniorCitizen* - Whether the customer is senior (Boolean type).
  - *Partner* - whether the cutomer has a partner.
  - *Dependents* - whether the customer has dependents.
- `internet.csv` — information about Internet services
  - *customerID* - unique code assigned to each client.
  - *InternetService* - how the network is set up: DSL or fiber optic cable.
  - *OnlineSecurity* - whether the customer got the malicious website blocker option.
  - *OnlineBackup* - whether the customer got the cloud file storage and data backup option.
  - *DeviceProtection* - whether the customer got the antivirus software option.
  - *TechSupport* - whether the customer got the dedicated technical support line option.
  - *StreamingTV* - whether the customer got the TV streaming option.
  - *StreamingMovies* - whether the customer got the movie directory option.
- `phone.csv` — information about telephone services
  - *customerID* - unique code assigned to each client.
  - *MultipleLines* - whether the telephone is connected to several lines simultaneously.

### Libraries used:
pandas, 
numpy, 
matplotlib, 
seaborn, 
pandas_profiling, 
datetime, 
sklearn, 
imblearn, 
catboost
