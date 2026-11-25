# Concrete Slump Prediction Using KNN Regression

## Project Overview

This project implements the K-Nearest Neighbors (KNN) Regression algorithm to predict the slump value of concrete based on its ingredient composition and properties.

The objective is to understand how different concrete components influence concrete workability and to predict slump values using machine learning.

## Dataset

- **Dataset:** Concrete Slump Test Dataset
- **Problem Type:** Regression
- **Target Variable:** `SLUMP (cm)`
- **Dataset Size:** 103 observations

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Data Loading and Understanding
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Selection
5. Train-Test Split
6. Feature Scaling using StandardScaler
7. KNN Regression Model Implementation
8. Distance Metric Comparison
9. Model Evaluation

## Algorithm

**K-Nearest Neighbors (KNN) Regression**

Different distance metrics were explored to understand their impact on model performance:

- Manhattan Distance
- Euclidean Distance
- Chebyshev Distance

## Model Evaluation Metrics

The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Model Results

The best reported configuration was:

- **Best Distance Metric:** Manhattan
- **Best K Value:** 3

| Evaluation Metric | Result |
|---|---:|
| MAE | 4.05 |
| MSE | 28.25 |
| RMSE | 5.32 |
| R² Score | 0.463 |

## Project Structure

```text
Concrete-Slump-Prediction-Using-KNN/
│
├── Concrete_Slump_Prediction.ipynb
├── slump_test.csv
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Clone this repository:

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the project notebook and execute the cells sequentially.

## Conclusion

This project demonstrates the application of KNN Regression for predicting concrete slump values. Different distance metrics were explored, and model performance was evaluated using regression metrics to understand the predictive capability of the algorithm.
