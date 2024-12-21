# Data Science Datasets Collection

Welcome to the **Data Science Datasets Collection** repository! This is a curated collection of popular datasets for data science projects, learning, and experimentation. Whether you're a beginner exploring the fundamentals of data science or an experienced practitioner looking for new datasets, this repository aims to be a valuable resource.

---

## 🎯 Purpose
This repository provides datasets that:
- Help in building machine learning models.
- Facilitate experimentation with data cleaning, preprocessing, and visualization techniques.
- Serve as a foundation for portfolio-building projects.

---

## 📂 Available Datasets

### 1. **Heart Disease Dataset**
- **Description**: Contains medical data used to predict the likelihood of heart disease in a patient.
- **Use Cases**: Classification, predictive modeling, and exploratory data analysis.
- **Data Dictionary**:
  - **Age**: Age of the patient.
  - **Sex**: Gender of the patient (1 = male, 0 = female).
  - **Chest Pain Type**: Type of chest pain experienced (e.g., typical angina, atypical angina).
  - **Resting Blood Pressure**: Blood pressure at rest.
  - **Cholesterol**: Serum cholesterol levels in mg/dl.
  - **Max Heart Rate Achieved**: Maximum heart rate achieved during exercise.
  - **Target**: Diagnosis of heart disease (1 = disease, 0 = no disease).
- **File Reference**: [heart_disease.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/heart_disease.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/heart_disease.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

~

### 2. **Housing Prices Dataset**
- **Description**: Includes various features affecting housing prices in a region, useful for regression tasks.
- **Use Cases**: Regression modeling, feature engineering, and visualization.
- **Data Dictionary**:
  - **Lot Area**: Lot size in square feet.
  - **Overall Quality**: Rates the overall material and finish of the house (1 to 10).
  - **Year Built**: Year the house was constructed.
  - **Sale Price**: Price of the property in dollars.
- **File Reference**: [housing_prices.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/housing_prices.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/housing_prices.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

~

### 3. **Loans Dataset**
- **Description**: Features financial data used to assess loan eligibility and default risk.
- **Use Cases**: Classification, predictive modeling, and risk assessment.
- **Data Dictionary**:
  - **Loan Amount**: The total amount of loan applied for.
  - **Loan Term**: Duration of the loan in months.
  - **Credit Score**: Applicant's credit score.
  - **Loan Status**: Status of the loan (approved or rejected).
- **File Reference**: [loans.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/loans.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/loans.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

~

### 4. **Google Play Store Dataset**
- **Description**: Provides data on various apps available in the Google Play Store, including features like category, rating, and number of installs.
- **Use Cases**: Classification, clustering, exploratory data analysis, and recommendation systems.
- **Data Dictionary**:
  - **App**: Name of the application.
  - **Category**: Category of the application (e.g., Education, Games).
  - **Rating**: Average user rating of the app (out of 5).
  - **Installs**: Number of times the app has been installed.
  - **Price**: Price of the app in dollars.
- **File Reference**: [google_play_store.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/google_play_store.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/google_play_store.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

~

### 5. **Titanic Dataset**
- **Description**: Classic dataset containing details of Titanic passengers, including their survival status, class, age, and more.
- **Use Cases**: Classification tasks, survival analysis, and feature engineering.
- **Data Dictionary**:
  - **PassengerId**: Unique identifier for each passenger.
  - **Survived**: Survival status (1 = survived, 0 = not survived).
  - **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
  - **Name**: Name of the passenger.
  - **Sex**: Gender of the passenger.
  - **Age**: Age of the passenger.
  - **SibSp**: Number of siblings or spouses aboard the Titanic.
  - **Parch**: Number of parents or children aboard the Titanic.
  - **Ticket**: Ticket number.
  - **Fare**: Fare paid by the passenger.
  - **Cabin**: Cabin number.
  - **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
- **File Reference**: [titanic.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/titanic.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/titanic.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

~

### 6. **Iris Dataset**
- **Description**: A classic dataset containing measurements of iris flowers (sepal length, sepal width, petal length, petal width) and their species (Setosa, Versicolor, Virginica).
- **Use Cases**: Classification, clustering, and visualization.
- **Data Dictionary**:
  - **Sepal Length**: Length of the sepal in cm.
  - **Sepal Width**: Width of the sepal in cm.
  - **Petal Length**: Length of the petal in cm.
  - **Petal Width**: Width of the petal in cm.
  - **Species**: The species of the iris flower (Setosa, Versicolor, Virginica).
- **File References**: [iris.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/iris.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/iris.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

  **From Scikit-learn Library**:
  ```python
  from sklearn.datasets import load_iris
  import pandas as pd

  # Load the Iris dataset from sklearn
  iris = load_iris()

  # Convert to a DataFrame
  iris_df = pd.DataFrame(data=iris.data, columns=iris.feature_names)
  iris_df['target'] = iris.target
  ```

~

### 7. **Media Company Dataset**
- **Description**: Contains data related to content performance and marketing metrics for a media company. The dataset includes details like impressions, clicks, conversions, and spends for different campaigns.
- **Use Cases**: Exploratory data analysis, campaign optimization, and predictive modeling.
- **Data Dictionary**:
  - **Impressions**: Number of times the content was shown.
  - **Clicks**: Number of times the content was clicked.
  - **Conversions**: Number of successful actions taken by users (e.g., purchases, sign-ups).
  - **Spend**: Total money spent on the campaign.
  - **CTR**: Click-through rate, calculated as (Clicks / Impressions).
- **File Reference**: [mediacompany.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/mediacompany.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/mediacompany.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

~

### 8. **Bike Sharing Dataset**
- **Description**: Contains data on bike-sharing systems, including features such as date, season, weather, and the count of bikes rented.
- **Use Cases**: Time-series analysis, regression modeling, and demand forecasting.
- **Data Dictionary**:
  - **Datetime**: Date and time of the bike rentals.
  - **Season**: Season of the year (1 = spring, 2 = summer, 3 = fall, 4 = winter).
  - **Holiday**: Whether the day is a holiday (1 = yes, 0 = no).
  - **Workingday**: Whether the day is a working day (1 = yes, 0 = no).
  - **Weather**: Weather condition (e.g., clear, misty, rainy).
  - **Temp**: Temperature in Celsius.
  - **Humidity**: Relative humidity.
  - **Windspeed**: Wind speed.
  - **Casual**: Number of casual (non-registered) users who rented bikes.
  - **Registered**: Number of registered users who rented bikes.
  - **Count**: Total number of bike rentals.
- **File Reference**: [bikesharing.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/bikesharing.csv)
   ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/bikesharing.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```
~

### 9. **Telecom Churn Dataset**

- **Description**: Contains customer data, internet service details, and overall churn status for a telecom company. It integrates multiple dimensions, including customer demographics, service usage, and churn status.
- **Use Cases**: Classification tasks, churn prediction, customer segmentation, and retention strategy modeling.
- **Data Dictionary**:
  - **CustomerID**: Unique identifier for each customer.
  - **Gender**: Gender of the customer (Male, Female).
  - **SeniorCitizen**: Whether the customer is a senior citizen (1 = Yes, 0 = No).
  - **Partner**: Whether the customer has a partner (Yes, No).
  - **Dependents**: Whether the customer has dependents (Yes, No).
  - **Tenure**: Number of months the customer has stayed with the company.
  - **PhoneService**: Whether the customer has a phone service (Yes, No).
  - **MultipleLines**: Whether the customer has multiple lines (Yes, No, No phone service).
  - **InternetService**: Type of internet service (DSL, Fiber optic, None).
  - **OnlineSecurity**: Whether the customer has online security service (Yes, No, No internet service).
  - **OnlineBackup**: Whether the customer has online backup service (Yes, No, No internet service).
  - **DeviceProtection**: Whether the customer has device protection service (Yes, No, No internet service).
  - **TechSupport**: Whether the customer has tech support service (Yes, No, No internet service).
  - **StreamingTV**: Whether the customer has streaming TV service (Yes, No, No internet service).
  - **StreamingMovies**: Whether the customer has streaming movies service (Yes, No, No internet service).
  - **Contract**: Customer’s contract type (Month-to-month, One year, Two year).
  - **PaperlessBilling**: Whether the customer uses paperless billing (Yes, No).
  - **PaymentMethod**: Payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).
  - **MonthlyCharges**: Monthly charges for the customer.
  - **TotalCharges**: Total charges paid by the customer.
  - **Churn**: Whether the customer churned (Yes, No).

- **Supporting Files**:
  - **telecom_churn_data.csv**: Main data file.
  - **telecom_churn_customer_data.csv**: Supplementary customer demographic data.
  - **telecom_churn_internet_data.csv**: Supplementary internet service details.
  - **telecom_churn_datadictionary.csv**: Data dictionary for the dataset.

- **File Reference**: [telecom_churn_data.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/telecom_churn_data.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/telecom_churn_data.csv'
  df = pd.read_csv(url)
  print(df.head())


---

## 🧩 Contributing
Contributions are welcome! If you have a dataset to share or suggestions to improve the repository:
1. Fork the repository.
2. Add your dataset in the appropriate format (CSV preferred).
3. Submit a pull request with a brief description of the dataset.

---

## 📜 License
This repository is licensed under the MIT License. Feel free to use the datasets for educational and non-commercial purposes.

---

## 🌟 Acknowledgments
Special thanks to the data science community for inspiring this repository. The datasets included here are sourced from public domains and are credited accordingly.

---

### 🔗 Stay Connected
- [LinkedIn](https://www.linkedin.com/in/your-profile)
- [Portfolio](https://your-portfolio.com)
- [GitHub](https://github.com/your-username)
