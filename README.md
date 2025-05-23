# Data Science Datasets Collection

Welcome to the **Data Science Datasets Collection** repository! This is a curated collection of popular datasets for data science projects, learning, and experimentation. Whether you're a beginner exploring the fundamentals of data science or an experienced practitioner looking for new datasets, this repository aims to be a valuable resource.

---

- [🎯 Purpose](#-purpose)
- [📂 Available Datasets](#-available-datasets)
- [Heart Disease Dataset](#1-heart-disease-dataset)
- [Housing Prices Dataset](#2-housing-prices-dataset)
- [Loans Dataset](#3-loans-dataset)
- [Google Play Store Dataset](#4-google-play-store-dataset)
- [Titanic Dataset](#5-titanic-dataset)
- [Iris Dataset](#6-iris-dataset)
- [Media Company Dataset](#7-media-company-dataset)
- [Bike Sharing Dataset](#8-bike-sharing-dataset)
- [Telecom Churn Dataset](#9-telecom-churn-dataset)
- [Car Evaluation Dataset](#10-car-evaluation-dataset)
- [Reliance Stock Dataset](#11-reliance-stock-dataset)
- [Pulsar Star Dataset](#12-pulsar-star-dataset)
- [Wine Quality Dataset](#13-wine-quality-dataset)
- [Diabetes Dataset](#14-diabetes-dataset)
- [Home Loan Dataset](#15-home-loan-dataset)
- [Online Retail Dataset](#16-online-retail-dataset)
- [Country Dataset](#17-country-dataset)
- [Mall Customers Dataset](#18-mall-customers-dataset)
- [Lead Scoring Dataset](#19-lead-scoring-dataset)
- [Motion Sensor Dataset](#20-motion-sensor-dataset)
- [Mental Health Text Dataset](#21-mental-health-text-dataset)
- [🧩 Contributing](#-contributing)
- [📜 License](#-license)
- [🌟 Acknowledgments](#-acknowledgments)
- [🔗 Stay Connected](#-stay-connected)

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
- **Description**: This dataset contains features influencing housing prices, providing a foundation for regression and machine learning tasks.
- **Use Cases**: Predictive modeling, feature engineering, and exploratory data analysis.
- **Data Dictionary**:
  - **price**: Description not provided yet. (Data Type: int64)
  - **area**: Description not provided yet. (Data Type: int64)
  - **bedrooms**: Description not provided yet. (Data Type: int64)
  - **bathrooms**: Description not provided yet. (Data Type: int64)
  - **stories**: Description not provided yet. (Data Type: int64)
  - **mainroad**: Description not provided yet. (Data Type: object)
  - **guestroom**: Description not provided yet. (Data Type: object)
  - **basement**: Description not provided yet. (Data Type: object)
  - **hotwaterheating**: Description not provided yet. (Data Type: object)
  - **airconditioning**: Description not provided yet. (Data Type: object)
  - **parking**: Description not provided yet. (Data Type: int64)
  - **prefarea**: Description not provided yet. (Data Type: object)
  - **furnishingstatus**: Description not provided yet. (Data Type: object)
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
- **File References**: [iris.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/iris-dataset/iris.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/iris-dataset/iris.csv'
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

~

### 10. **Car Evaluation Dataset**

- **Description**: Contains data about car evaluations based on various attributes, with a focus on safety, maintenance costs, and overall acceptability.
- **Use Cases**: Classification tasks, decision tree modeling, and feature importance analysis.

- **Data Dictionary**:
  - **Buying**: Buying price (values: vhigh, high, med, low).
  - **Maint**: Maintenance cost (values: vhigh, high, med, low).
  - **Doors**: Number of doors (values: 2, 3, 4, 5more).
  - **Persons**: Capacity in terms of persons to carry (values: 2, 4, more).
  - **Lug_boot**: Size of luggage boot (values: small, med, big).
  - **Safety**: Estimated safety of the car (values: low, med, high).
  - **Class**: Overall evaluation of the car (values: unacc, acc, good, vgood).

- **File Reference**: [car_evaluation.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/car_evaluation.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/car_evaluation.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

~

### 11. **Reliance Stock Dataset**

- **Description**: Historical stock data of Reliance Industries, including daily open, high, low, and closing prices, along with trading volume. This dataset is used for time-series analysis and stock price forecasting.
- **Use Cases**: Time-series forecasting, stock price prediction, financial trend analysis, and LSTM-based deep learning projects.

- **Data Dictionary**:
  - **Date**: The date of the stock trading day.
  - **Open**: The opening price of the stock.
  - **High**: The highest price of the stock during the trading day.
  - **Low**: The lowest price of the stock during the trading day.
  - **Close**: The closing price of the stock.
  - **Adj Close**: Adjusted closing price accounting for splits and dividends.
  - **Volume**: The number of shares traded during the trading day.

- **File Reference**: [reliance_stock.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/reliance_stock.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/reliance_stock.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

~

### 12. Pulsar Star Dataset

- **Description**: This dataset contains information about candidates for pulsar stars collected during the High Time Resolution Universe Survey. Pulsars are a type of neutron star and are discovered through their unique radio emission patterns. The dataset is used to classify pulsar stars versus non-pulsar candidates based on several signal-processing metrics.
- **Use Cases**: Classification tasks, exploratory data analysis, feature engineering, and model evaluation.

- **Data Dictionary**:
  - **Mean of the integrated profile**: Mean value of the integrated radio frequency signal.
  - **Standard deviation of the integrated profile**: Spread of values for the integrated signal.
  - **Excess kurtosis of the integrated profile**: Measure of the "tailedness" of the distribution of the integrated signal.
  - **Skewness of the integrated profile**: Measure of the asymmetry of the distribution of the integrated signal.
  - **Mean of the DM-SNR curve**: Mean signal-to-noise ratio curve for the dispersion measure.
  - **Standard deviation of the DM-SNR curve**: Spread of values in the signal-to-noise ratio curve.
  - **Excess kurtosis of the DM-SNR curve**: Tailedness of the signal-to-noise ratio curve.
  - **Skewness of the DM-SNR curve**: Asymmetry in the signal-to-noise ratio curve.
  - **Class**: Target variable (1 = pulsar star, 0 = non-pulsar candidate).

- **File Reference**: [pulsar_star_dataset.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/pulsar_star_dataset.csv)
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/pulsar_star_dataset.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

~

### 13. Wine Quality Dataset

### Wine Dataset

- **Description**: This dataset contains information about different wine samples and their chemical properties. It includes details such as acidity, sugar content, pH levels, and quality ratings. The dataset is widely used for classification tasks to predict wine quality based on its features.
- **Use Cases**: Classification tasks, feature importance analysis, exploratory data analysis, and regression modeling.

- **Data Dictionary**:
  - **fixed acidity**: The fixed acidity of the wine (e.g., tartaric acid content).
  - **volatile acidity**: Acetic acid content, which can add an unpleasant vinegar taste.
  - **citric acid**: The amount of citric acid present, which adds freshness to wines.
  - **residual sugar**: The amount of sugar remaining after fermentation.
  - **chlorides**: Salt content in the wine.
  - **free sulfur dioxide**: The free form of SO₂, which prevents microbial growth and oxidation.
  - **total sulfur dioxide**: Total SO₂ content, including bound and free forms.
  - **density**: The density of the wine, which can indicate sugar and alcohol content.
  - **pH**: A measure of the wine’s acidity.
  - **sulphates**: A wine additive that contributes to sulfur dioxide levels.
  - **alcohol**: Alcohol content by volume.
  - **quality**: Quality score of the wine (0 to 10).
  - **red**: Indicator for red wine (1 = red wine, 0 = not red wine).
  - **white**: Indicator for white wine (1 = white wine, 0 = not white wine).

- **File Reference**: [wine.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/wine.csv)
  ```python
  import pandas as pd

  # URL for the dataset
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/wine.csv'

  # Load the dataset
  df = pd.read_csv(url)

  # Print the first 5 rows to verify
  print(df.head())
  ```

~

### 14. Diabetes Dataset

- **Description**: This dataset contains information about various health metrics and medical test results that can be used to predict the onset of diabetes. The target variable indicates whether the patient has diabetes (1) or not (0). This dataset is widely used for binary classification problems, especially in healthcare-related machine learning projects.
- **Use Cases**: Classification tasks, feature engineering, exploratory data analysis, and predictive modeling.

- **Data Dictionary**:
  - **Pregnancies**: Number of times the patient has been pregnant.
  - **Glucose**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test.
  - **BloodPressure**: Diastolic blood pressure (mm Hg).
  - **SkinThickness**: Triceps skin fold thickness (mm).
  - **Insulin**: 2-Hour serum insulin (mu U/ml).
  - **BMI**: Body mass index (weight in kg/(height in m)^2).
  - **DiabetesPedigreeFunction**: Diabetes pedigree function (a function that scores the likelihood of diabetes based on family history).
  - **Age**: Age of the patient (years).
  - **Outcome**: Target variable (1 = diabetes positive, 0 = diabetes negative).

- **File Reference**: [diabetes.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/diabetes.csv)
  ```python
  import pandas as pd

  # URL for the dataset
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/diabetes.csv'

  # Load the dataset
  df = pd.read_csv(url)

  # Print the first 5 rows to verify
  print(df.head())
  ```

~

### 15. Home Loan Dataset

- **Description**: This dataset contains information about loan applications, including loan amount, interest rate, employment details, income, and loan status. The target variable indicates whether the loan was fully paid or charged off. This dataset is ideal for binary classification tasks in the financial domain.
- **Use Cases**: Classification tasks, risk analysis, exploratory data analysis, and feature engineering.

- **Data Dictionary**:
  - **id**: Unique identifier for each loan application.
  - **loan_amnt**: Loan amount requested by the applicant (numerical).
  - **funded_amnt**: Amount that was sanctioned by the bank (numerical).
  - **int_rate**: Interest rate on the loan (percentage).
  - **installment**: Monthly installment amount (numerical).
  - **emp_length**: Length of the applicant's employment (e.g., `<1 year`, `10+ years`).
  - **annual_inc**: Applicant's annual income (numerical).
  - **loan_status**: Classified as whether it is "High Risk", "Low Risk" and "Medium Risk".

- **File Reference**: [home-loan.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/home-loan.csv)
  ```python
  import pandas as pd

  # URL for the dataset
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/home-loan.csv'

  # Load the dataset
  df = pd.read_csv(url)

  # Print the first 5 rows to verify
  print(df.head())
  ```

~

### 16. Online Retail Dataset

- **Description**: This dataset contains transactional data from a UK-based online retailer. It includes information about invoices, products, quantities sold, customer details, and geographical locations of transactions. This dataset is ideal for tasks such as customer segmentation, sales analysis, market basket analysis, and recommendation system development.

- **Use Cases**: 
  - Customer segmentation and clustering.
  - Market basket analysis for association rule mining.
  - Sales and revenue trend analysis.
  - Anomaly detection for fraud mitigation.
  - Building recommendation systems.
  - Forecasting sales and inventory.

- **Data Dictionary**:
  - **InvoiceNo**: Unique identifier for each invoice (categorical).
  - **StockCode**: Unique identifier for each product (categorical).
  - **Description**: Description of the product (text).
  - **Quantity**: Number of units purchased (numerical).
  - **InvoiceDate**: Date and time of the transaction (datetime).
  - **UnitPrice**: Price per unit of the product (numerical).
  - **CustomerID**: Unique identifier for the customer (categorical, some missing values).
  - **Country**: Country where the order was placed (categorical).

- **File Reference**: [online-retail.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/online-retail.csv)

  ```python
  import pandas as pd

  # URL for the dataset
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/online-retail.csv'

  # Load the dataset
  df = pd.read_csv(url, encoding='latin1')

  # Print the first 5 rows to verify
  print(df.head())
  ```

~

### 17. Country Dataset

- **Description**: This dataset contains various socio-economic and health-related metrics for countries worldwide. It includes data on child mortality, health expenditure, trade (exports and imports), income levels, inflation rates, and GDP. The dataset is useful for analyzing global development indicators, exploring correlations between economic and health variables, and conducting predictive modeling.

- **Use Cases**:  
  - Exploring correlations between economic indicators and health outcomes.  
  - Predictive modeling for development indices.  
  - Clustering countries based on socio-economic factors.  
  - Trend analysis of economic growth and health expenditure.  
  - Visualizations for global economic and health disparities.

- **Data Dictionary**:  
  - **country**: Name of the country (categorical).  
  - **child_mort**: Child mortality rate, deaths per 1000 live births (numerical).  
  - **exports**: Exports as a percentage of GDP (numerical).  
  - **health**: Health expenditure as a percentage of GDP (numerical).  
  - **imports**: Imports as a percentage of GDP (numerical).  
  - **income**: Per capita income in USD (numerical).  
  - **inflation**: Inflation rate, annual percentage (numerical).  
  - **life_expec**: Life expectancy in years (numerical).  
  - **total_fer**: Total fertility rate, average number of children per woman (numerical).  
  - **gdpp**: GDP per capita in USD (numerical).

- **File Reference**: [country-data.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/country-data.csv)

  ```python
  import pandas as pd

  # URL for the dataset
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/country-data.csv'

  # Load the dataset
  df = pd.read_csv(url)

  # Print the first 5 rows to verify
  print(df.head())
  ```

~

### 18. Mall Customers Dataset

- **Description**: This dataset contains data about customers of a mall, including demographic details, spending habits, and income levels. It is commonly used for customer segmentation tasks and offers insights into consumer behavior patterns for targeted marketing.

- **Use Cases**:  
  - Customer segmentation using clustering techniques.  
  - Analysis of spending patterns across age groups and genders.  
  - Correlation analysis between annual income and spending scores.  
  - Identifying high-value customer groups for marketing campaigns.  
  - Building predictive models for personalized recommendations.

- **Data Dictionary**:  
  - **CustomerID**: Unique identifier for each customer (categorical).  
  - **Gender**: Gender of the customer (categorical).  
  - **Age**: Age of the customer in years (numerical).  
  - **Annual Income (k$)**: Annual income of the customer in thousand dollars (numerical).  
  - **Spending Score (1-100)**: Spending score assigned to the customer based on their spending behavior and purchasing habits (numerical).

- **File Reference**: [mall_customers.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/mall_customers.csv)

  ```python
  import pandas as pd

  # URL for the dataset
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/mall_customers.csv'

  # Load the dataset
  df = pd.read_csv(url)

  # Print the first 5 rows to verify
  print(df.head())
  ```

~

### 19. Lead Scoring Dataset

- **Description**:  
  This dataset is designed for lead scoring and analysis, helping businesses identify which leads are more likely to convert into customers. It includes information on customer demographics, activities, preferences, and lead quality indicators. The dataset is commonly used in marketing analytics and predictive modeling for lead prioritization.

- **Use Cases**:  
  - Predicting the likelihood of lead conversion using machine learning models.  
  - Analyzing customer behavior patterns (e.g., time spent on the website, visits).  
  - Identifying high-quality leads based on activity scores and preferences.  
  - Segmenting leads based on source, activity level, and demographics.  
  - Optimizing marketing campaigns by understanding lead origins and preferences.

- **Data Dictionary**:  
  - **Prospect ID**: Unique identifier for each customer (categorical).  
  - **Lead Number**: Lead number assigned to each lead procured (numerical).  
  - **Lead Origin**: Source through which the customer was identified as a lead (categorical).  
  - **Lead Source**: Indicates the specific source of the lead, such as Google, Organic Search, or Olark Chat (categorical).  
  - **Do Not Email**: Indicates whether the customer opted out of receiving emails (binary).  
  - **Do Not Call**: Indicates whether the customer opted out of receiving calls (binary).  
  - **Converted**: Target variable indicating whether a lead was successfully converted (binary).  
  - **TotalVisits**: Total number of visits made by the customer to the website (numerical).  
  - **Total Time Spent on Website**: Total time (in seconds) spent by the customer on the website (numerical).  
  - **Page Views Per Visit**: Average number of pages viewed per visit by the customer (numerical).  
  - **Last Activity**: Most recent activity performed by the customer (categorical).  
  - **Country**: Country of the customer (categorical).  
  - **Specialization**: Industry domain in which the customer worked (categorical).  
  - **How did you hear about X Education**: Source from which the customer learned about X Education (categorical).  
  - **What is your current occupation**: Indicates whether the customer is employed, unemployed, or a student (categorical).  
  - **What matters most to you in choosing this course**: Indicates the customer’s primary motive for taking the course (categorical).  
  - **Search**: Indicates whether the customer encountered the course through search (binary).  
  - **Magazine**: Indicates whether the customer encountered the course through a magazine (binary).  
  - **Newspaper Article**: Indicates whether the customer encountered the course through a newspaper article (binary).  
  - **X Education Forums**: Indicates whether the customer encountered the course through forums (binary).  
  - **Newspaper**: Indicates whether the customer encountered the course through a newspaper (binary).  
  - **Digital Advertisement**: Indicates whether the customer encountered the course through a digital advertisement (binary).  
  - **Through Recommendations**: Indicates whether the customer was referred by recommendations (binary).  
  - **Receive More Updates About Our Courses**: Indicates whether the customer opted for updates about the course (binary).  
  - **Tags**: Tags assigned to the lead indicating the current status (categorical).  
  - **Lead Quality**: Quality score assigned to the lead based on data and intuition (categorical).  
  - **Update me on Supply Chain Content**: Indicates whether the customer opted for supply chain content updates (binary).  
  - **Get updates on DM Content**: Indicates whether the customer opted for digital marketing content updates (binary).  
  - **Lead Profile**: A lead-level categorization based on the customer’s profile (categorical).  
  - **City**: City of the customer (categorical).  
  - **Asymmetrique Activity Index**: Activity-based index score for the customer (numerical).  
  - **Asymmetrique Profile Index**: Profile-based index score for the customer (numerical).  
  - **Asymmetrique Activity Score**: Activity score assigned to the customer (numerical).  
  - **Asymmetrique Profile Score**: Profile score assigned to the customer (numerical).  
  - **I agree to pay the amount through cheque**: Indicates whether the customer agreed to pay via cheque (binary).  
  - **A free copy of Mastering The Interview**: Indicates whether the customer opted for a free copy of "Mastering the Interview" (binary).  
  - **Last Notable Activity**: Last notable activity performed by the customer (categorical).

- **File Reference**: [lead-scoring.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/lead-scoring.csv)

```python
import pandas as pd

# URL for the dataset
url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/lead-scoring.csv'

# Load the dataset
df = pd.read_csv(url)

# Display the first 5 rows of the dataset
print(df.head())
```

~

### 20. Motion Sensor Dataset

- **Description**:  
  This dataset contains motion sensor data collected from an MPU6050 sensor. It provides essential insights into various physical activities through accelerometer and gyroscope data. The dataset is designed for real-time activity classification and motion analysis. Applications include fitness tracking, sports performance monitoring, and AI-powered activity recognition systems.

- **Use Cases**:  
  - Training machine learning models for activity recognition.  
  - Developing real-time AIoT systems for fitness tracking.  
  - Analyzing motion patterns for health and performance monitoring.  
  - Evaluating and predicting physical activities in rehabilitation and sports.  

- **Data Dictionary**:  
  - **epoch**: Timestamp of the data collection (numerical).  
  - **Accelerometer_x**: Acceleration along the x-axis (numerical).  
  - **Accelerometer_y**: Acceleration along the y-axis (numerical).  
  - **Accelerometer_z**: Acceleration along the z-axis (numerical).  
  - **Gyroscope_x**: Angular velocity around the x-axis (numerical).  
  - **Gyroscope_y**: Angular velocity around the y-axis (numerical).  
  - **Gyroscope_z**: Angular velocity around the z-axis (numerical).  
  - **Label**: Activity performed (`bench`, `ohp`, `dead`, `squat`, `row`, `rest`) (categorical). Each label represents a specific physical activity:  
    - `bench`: Bench press.  
    - `ohp`: Overhead press.  
    - `dead`: Deadlift.  
    - `squat`: Squats.  
    - `row`: Barbell rows.  
    - `rest`: Inactivity or resting periods.

- **File Reference**: [motion_sensor.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/motion_sensor.csv)

```python
import pandas as pd

# URL for the dataset
url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/motion_sensor.csv'

# Load the dataset
df = pd.read_csv(url)

# Display the first 5 rows of the dataset
print(df.head())
```

~

### 21. Mental Health Text Dataset

**Description**: This dataset contains textual data labeled according to indications of mental health concerns, specifically identifying content associated with mental health issues or distress.

**Use Cases**: Sentiment analysis, text classification, NLP-based mental health detection, exploratory data analysis, and machine learning classification tasks.

**Data Dictionary**:

  - **text**: The textual content collected from various sources, potentially containing expressions or indications of mental health conditions or distress. (Data Type: object)
  - **label**: Binary indicator specifying whether the text indicates a mental health issue (1) or not (0). (Data Type: int64)

File Reference: [mental_health.csv](https://github.com/vmahawar/data-science-datasets-collection/raw/main/mental_health.csv)

```python
import pandas as pd
url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/mental_health.csv'
df = pd.read_csv(url)
print(df.head())
```

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
