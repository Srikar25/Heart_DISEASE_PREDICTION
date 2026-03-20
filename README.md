# ❤️ Heart Disease Data Analysis & Preprocessing

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **data
preprocessing** on a heart disease dataset to understand feature
relationships and prepare the data for machine learning modeling.

The notebook explores patient health attributes, analyzes correlations
between variables, handles categorical encoding, and applies feature
scaling to create a model‑ready dataset.

The goal is to identify patterns that may help predict the presence of
heart disease.

------------------------------------------------------------------------

## 📂 Project Structure

    .
    ├── analysis.ipynb        # Main analysis notebook
    ├── data/
    │   └── train.csv         # Dataset used for analysis
    └── README.md             # Project documentation

------------------------------------------------------------------------

## 🧠 Dataset Description

The dataset contains medical attributes describing patient health
conditions.

  Feature             Description                         Type
  ------------------- ----------------------------------- -------------
  id                  Patient identifier                  Numerical
  Age                 Age of the patient                  Continuous
  Sex                 Male / Female                       Categorical
  Chest Pain Type     Type of chest pain                  Categorical
  BP                  Blood pressure                      Continuous
  Cholesterol         Cholesterol level                   Continuous
  FBS over 120        Fasting blood sugar                 Categorical
  EKG Results         ECG test results                    Categorical
  Max HR              Maximum heart rate achieved         Continuous
  Exercise Angina     Exercise-induced angina             Categorical
  ST Depression       ST depression value                 Continuous
  Slope of ST         Slope of peak exercise ST segment   Categorical
  Number of Vessels   Fluoroscopy vessels count           Categorical
  Thallium            Thallium stress test result         Categorical
  Heart Disease       Target variable                     Categorical

------------------------------------------------------------------------

## 🔎 Analysis Performed

### 1️⃣ Data Exploration

-   Loaded dataset using **Pandas**
-   Previewed data structure
-   Checked missing values
-   Examined data types and feature distributions
-   Counted unique values per column

### 2️⃣ Exploratory Data Analysis (EDA)

-   Correlation analysis between numerical variables
-   Identification of feature relationships
-   Visualization using Matplotlib & Seaborn

### Key Insights

-   No strong linear correlations between features (\|r\| \< 0.25)
-   Moderate relationship between:
    -   **Max Heart Rate** and **ST Depression**
-   Low multicollinearity --- suitable for machine learning models
-   Possible presence of non-linear relationships

### 3️⃣ Data Preprocessing

-   Encoding categorical variables
-   Target variable transformation
-   Correlation analysis with encoded dataset
-   Feature scaling using `StandardScaler`

------------------------------------------------------------------------

## ⚙️ Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn
-   Jupyter Notebook

------------------------------------------------------------------------

## ▶️ How to Run the Project

### 1. Clone the repository

``` bash
git clone https://github.com/your-username/heart-disease-analysis.git
cd heart-disease-analysis
```

### 2. Install dependencies

``` bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Run the notebook

``` bash
jupyter notebook analysis.ipynb
```

------------------------------------------------------------------------

## 📊 Future Improvements

-   Build classification models (Logistic Regression, Random Forest,
    etc.)
-   Feature engineering
-   Hyperparameter tuning
-   Model evaluation & comparison
-   Deployment as a prediction API or web app

------------------------------------------------------------------------

## 🎯 Objective

This project focuses on understanding medical data patterns and
preparing a clean dataset suitable for predictive modeling of heart
disease risk.

------------------------------------------------------------------------

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome!

------------------------------------------------------------------------

## 📜 License

This project is open-source and available under the MIT License.
