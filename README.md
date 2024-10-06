# 📊 Sales Prediction Using Machine Learning

This project demonstrates how to predict sales using machine learning models based on advertising expenditure data. By utilizing various machine learning techniques and hyperparameter tuning, this project explores the relationship between advertising spend and sales performance.

## 📖 Project Overview

The project implements and evaluates the following models:
- **Linear Regression**: A fundamental model to predict sales based on advertising data.
- **Lasso Regression**: A model that incorporates L1 regularization to reduce overfitting.
- **Grid Search with Cross-Validation**: A technique to fine-tune hyperparameters for optimal model performance.

## 📊 Dataset

The dataset used for this project contains advertising expenditures across various media (TV, radio, and newspaper) and their impact on sales. The CSV file can be found in the `Advertising.csv` file.

## 🚀 Installation

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/your-repo/SalesPrediction.git
   cd SalesPrediction
   ```

2. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

## 🛠️ Usage

1. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook SalesPrediction.ipynb
   ```

2. **Run all the cells** in the notebook to train and evaluate the models.

## 🧩 Models Implemented

- **Linear Regression**: Predicts sales based on a linear relationship with advertising data.
- **Lasso Regression**: Introduces L1 regularization to minimize the coefficients of less important features.

## ⚙️ Hyperparameter Tuning

- **GridSearchCV** is utilized to find the best combination of hyperparameters for the models. The following parameters are tuned:
  - `alpha` (for Lasso Regression)
  - `fit_intercept`
  - `max_iter`

## 📈 Results

The model performance is evaluated using the R-squared score. After tuning the hyperparameters, the Lasso model achieves an R-squared score of approximately **0.92** on the training data, indicating a strong fit.

### Sample Results:
- **Linear Regression R² Score**: 0.89
- **Lasso Regression R² Score**: 0.92

## 🧪 Key Libraries

- **`scikit-learn`**: For implementing machine learning models and cross-validation.
- **`pandas`**: For data manipulation and analysis.
- **`numpy`**: For numerical computations.

## 🔍 Conclusion

This project effectively demonstrates how advertising expenditures influence sales and how different regression models can predict future sales with reasonable accuracy. Future improvements could include:
- Exploring additional models like Ridge Regression.
- Implementing feature engineering for better prediction.
