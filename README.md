# House Price Prediction: Model Optimization & Comparison

An end-to-end machine learning pipeline predicting California house prices. Includes feature scaling, training multiple regression models (Linear, Ridge, Decision Tree), and comparative performance evaluation using RMSE and R²[cite: 1, 2].

## Overview
This repository contains a structured machine learning project focused on feature engineering, model optimization, and performance comparison[cite: 1]. Built as part of an Artificial Intelligence & Machine Learning portfolio, this system predicts median house values using the California Housing Dataset[cite: 1].

## Tech Stack
* **Language:** Python[cite: 1]
* **Libraries:** pandas, NumPy, scikit-learn, matplotlib[cite: 1, 2]
* **Environment:** Jupyter Notebook[cite: 1, 2]

## Machine Learning Pipeline
The project follows an industry-aligned ML workflow[cite: 1]:
1. **Data Preparation:** Separating input features ($X$) and target variables ($y$)[cite: 1, 2].
2. **Feature Scaling:** Applying `StandardScaler` to ensure fair learning across all numeric features and stabilize model performance[cite: 1, 2].
3. **Data Splitting:** Utilizing an 80/20 train-test split (`test_size=0.2`, `random_state=42`) to evaluate models on unseen data[cite: 1, 2].
4. **Model Training:** Training three distinct regression algorithms (Linear, Ridge, Decision Tree) to establish baselines and capture non-linear relationships[cite: 1, 2].
5. **Evaluation:** Comparing models using Root Mean Squared Error (RMSE) and R² Score metrics[cite: 1, 2].

## Results & Model Comparison
The models were evaluated based on their predictive accuracy (RMSE) and explanatory power (R²)[cite: 1]. 

| Model | RMSE | R² Score |
| :--- | :--- | :--- |
| **Linear Regression** | 0.745581 | 0.575788 |
| **Ridge Regression** | 0.745554 | 0.575819 |
| **Decision Tree** | 0.724234 | 0.599732 |

*(Note: Data derived from the California Housing Dataset evaluation[cite: 2].)*

## Conclusion
The **Decision Tree Regressor** was selected as the best-performing model[cite: 1]. It achieved the lowest RMSE (0.724234) and the highest R² Score (0.599732), demonstrating its ability to capture non-linear patterns within the housing features (such as location, income, and age) that the linear models missed[cite: 1, 2].

## How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/yourusername/your-repo-name.git)


2. Install the required dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib

```


3. Open the Jupyter Notebook:
```bash
jupyter notebook AI_ML_Task2_Model_Comparison.ipynb

```


4. Run all cells to execute the pipeline and view the actual vs. predicted visualization plots.

---



```

```
