# House Price Prediction using XGBoost

This project demonstrates how to perform house price prediction using the **Boston Housing Dataset** and an **XGBoost Regressor**. The workflow covers data loading, preprocessing, exploratory data analysis (EDA), model training, and performance evaluation.

---

## 📦 Libraries Used

* **NumPy** – Numerical operations
* **Pandas** – Data manipulation and analysis
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Dataset loading, preprocessing, model evaluation
* **XGBoost** – Gradient boosting regression model

---

## 📊 Dataset

The project uses the **Boston Housing Dataset**, which contains information about houses in Boston, including features like:

* Crime rate
* Number of rooms
* Property tax rate
* Accessibility to highways

The target variable is **house price**.

---

## 🛠️ Steps in the Project

### 1. Load the Dataset

The dataset is loaded using `sklearn.datasets.load_boston()`.

### 2. Convert to DataFrame

Create a pandas DataFrame and add the target column `price`.

### 3. Exploratory Data Analysis

* Check shape, missing values, summary statistics
* Compute correlations between features
* Plot a **correlation heatmap** to understand relationships

### 4. Prepare Data

Split the dataset into:

* **Features (X)** – all columns except price
* **Target (Y)** – price column

Use an 80/20 train-test split.

### 5. Build and Train the Model

Use **XGBRegressor** to train the model on the training data.

### 6. Model Evaluation

Metrics used:

* **R² Score** – how well the model fits the data
* **Mean Absolute Error (MAE)** – average absolute prediction error

Visualizations:

* Scatter plot of **Actual vs Predicted** prices

---

## 📈 Results

The model's performance is evaluated on both training and test datasets using R² and MAE. A scatter plot shows how closely predictions align with real values.

---

## ▶️ How to Run the Project

1. Install all required libraries:

```
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

2. Run the Python script in any environment (Jupyter Notebook, VS Code, PyCharm, etc.)

---

## 📌 Notes

* The Boston dataset is deprecated in newer versions of scikit-learn due to ethical concerns.
* Model performance may vary depending on hyperparameters.
* You can improve results using tuning techniques such as GridSearchCV.

---

## ✔️ Conclusion

This project demonstrates a complete machine learning workflow using XGBoost for regression. It includes data preprocessing, visualization, model training, and evaluation, helping beginners understand practical ML implementation.

---
