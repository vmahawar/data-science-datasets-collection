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
- **File Reference**:
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/heart_disease.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

### 2. **Housing Prices Dataset**
- **Description**: Includes various features affecting housing prices in a region, useful for regression tasks.
- **Use Cases**: Regression modeling, feature engineering, and visualization.
- **File Reference**:
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/housing_prices.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

### 3. **Loans Dataset**
- **Description**: Features financial data used to assess loan eligibility and default risk.
- **Use Cases**: Classification, predictive modeling, and risk assessment.
- **File Reference**:
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/loans.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```

### 4. **Google Play Store Dataset**
- **Description**: Provides data on various apps available in the Google Play Store, including features like category, rating, and number of installs.
- **Use Cases**: Classification, clustering, exploratory data analysis, and recommendation systems.
- **File Reference**:
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/google_play_store.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```  

### 5. **Titanic Dataset**
- **Description**: Classic dataset containing details of Titanic passengers, including their survival status, class, age, and more.
- **Use Cases**: Classification tasks, survival analysis, and feature engineering.
- **File Reference**:
  ```python
  import pandas as pd
  url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/titanic.csv'
  df = pd.read_csv(url)
  print(df.head())
  ```  
  
### 6. **Iris Dataset**
- **Description**: A classic dataset containing measurements of iris flowers (sepal length, sepal width, petal length, petal width) and their species (Setosa, Versicolor, Virginica).
- **Use Cases**: Classification, clustering, and visualization.
- **File References**:
  - **From CSV File**:
    ```python
    import pandas as pd
    url = 'https://github.com/vmahawar/data-science-datasets-collection/raw/main/iris.csv'
    df = pd.read_csv(url)
    print(df.head())
    ```
  - **From Scikit-learn Library**:
    ```python
    from sklearn.datasets import load_iris
    import pandas as pd

    # Load the Iris dataset from sklearn
    iris = load_iris()

    # Convert to a DataFrame
    iris_df = pd.DataFrame(data=iris.data, columns=iris.feature_names)
    iris_df['target'] = iris.target

    print(iris_df.head())
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
- [LinkedIn](https://www.linkedin.com/in/vijay-mahawar/)
- [Portfolio](https://www.vijay.mahawar.net/projects)
- [GitHub](https://github.com/vmahawar)
