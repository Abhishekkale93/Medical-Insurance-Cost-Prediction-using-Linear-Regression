# Medical-Insurance-Cost-Prediction-using-Linear-Regression

This project demonstrates how to use **Linear Regression** to predict the cost of medical insurance based on features such as age, BMI, smoking status, and more. It follows a standard machine learning pipeline from data preprocessing and exploratory analysis to model training and evaluation.

---

## Problem Statement

The objective of this project is to develop a regression model that accurately predicts the **insurance charges** of individuals based on their age, gender, BMI, number of children, smoking habits, and residential region. This prediction can help insurance providers assess the risk profile of customers and determine premiums more efficiently.

---

## Dataset Information

- **File**: `insurance.csv`
- **Observations**: 1338
- **Features**:
  - `age`
  - `sex`
  - `bmi`
  - `children`
  - `smoker`
  - `region`
  - `charges` *(target variable)*

---

## Project Workflow

### 1. **Data Preprocessing**
- Handled categorical variables using Label Encoding and One-Hot Encoding
- Verified no missing values
- Prepared features and labels for modeling

### 2. **Exploratory Data Analysis**
- Visualized feature distributions using histograms and boxplots
- Created a correlation heatmap to understand relationships between variables
- Analyzed the impact of smoking and BMI on insurance costs

### 3. **Model Training**
- Split the dataset into training and testing sets (80/20 split)
- Trained a Linear Regression model using scikit-learn

### 4. **Model Evaluation**
Evaluated the model using the following metrics for both training and test data:
- R-squared (R²)
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Results Interpretation

- **Smokers** were found to have significantly higher insurance charges.
- **BMI** and **age** also showed strong influence on the predicted charges.
- The model performs reasonably well, especially in identifying high-risk individuals.

---

## Conclusion

The Linear Regression model built in this project provides valuable insights into how different features impact medical insurance costs. While the model explains a significant portion of the variability, there is room for improvement through techniques such as **regularization**, **cross-validation**, or **advanced regression methods** like **Lasso** or **Ridge**.

---

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## Files

- "https://www.kaggle.com/datasets/mirichoi0218/insurance": The dataset
- `Medical_Insurance_Cost_Prediction.ipynb`: The notebook with code
- `README.md`: Project documentation

---

## How to Run

1. Clone the repository
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

