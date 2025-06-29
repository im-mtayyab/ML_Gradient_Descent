# Gradient Descent Regression Project 🚀

This project showcases the implementation of **Linear Regression** and **Polynomial Regression** using **Gradient Descent** to predict salaries and house prices, respectively. The tasks utilize the `Salary_data.csv` and `kc_house_data.csv` datasets, with detailed methodology and analysis provided in the accompanying report.

---

## 📖 Overview

This repository contains two machine learning tasks:

- **Linear Regression**: Predicts salaries based on years of experience using a univariate linear regression model optimized with gradient descent.
- **Polynomial Regression**: Predicts house prices based on features like square footage using a second-degree polynomial regression model, optimized with gradient descent.

Key techniques include data preprocessing, gradient descent optimization, feature engineering, and model evaluation with visualizations.

---

## 📂 Folder Structure

```
├── 📁 Linear Regression/
│   └── 📓 Salary_Prediction.ipynb
├── 📁 Polynomial Regression/
│   └── 📓 House_Price_Prediction.ipynb
└── 📄 Gradient_Descent_Report.pdf
```

- **Linear Regression/Salary_Prediction.ipynb**: Jupyter Notebook for salary prediction using linear regression on `Salary_data.csv`.
- **Polynomial Regression/House_Price_Prediction.ipynb**: Jupyter Notebook for house price prediction using polynomial regression on `kc_house_data.csv`.
- **Gradient_Descent_Report.pdf**: Comprehensive report detailing methodology, implementation, and analysis.

---

## 📊 Datasets

- **Salary_data.csv**: Contains 30 records with:
  - `YearsExperience`: Numerical value of work experience.
  - `Salary`: Annual income in local currency.
- **kc_house_data.csv**: Contains house data with features like `sqft_living`, `grade`, `sqft_above`, and `price`.

---

## 🛠️ Requirements

To run the notebooks, install the following Python libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone (https://github.com/im-mtayyab/ML_Gradient_Descent)
   ```
2. **Navigate to the project directory**:
   ```bash
   cd <ML_Gradient_Descent>
   ```
3. **Open Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
4. **Run the notebooks**:
   - For salary prediction: `Linear Regression/Salary_Prediction.ipynb`
   - For house price prediction: `Polynomial Regression/House_Price_Prediction.ipynb`

---

## 🌟 Key Features

- **Data Preprocessing**: 🧹 Normalization and standardization for faster convergence.
- **Gradient Descent**: 🔄 Manual implementation to optimize model parameters.
- **Visualizations**: 📈 Includes scatter plots, cost convergence plots, residual plots, and error histograms.
- **Evaluation Metrics**: 📏 Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R² Score.

---

## 📜 Report Summary

The `Gradient_Descent_Report.pdf` covers:

- **Dataset Details**: Description and preprocessing steps (e.g., handling outliers, feature scaling).
- **Gradient Descent Algorithm**: Explanation of optimization process and parameter updates.
- **Model Training & Evaluation**: Training process, convergence analysis, and performance metrics.
- **Visualizations**: Cost curves, gradient updates, residual plots, and error distributions.
- **Performance Factors**: Impact of feature scaling, stochastic gradient descent, and feature engineering.

---

## 🔗 References

- [Scikit-learn PolynomialFeatures](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.PolynomialFeatures.html) 📚
- [Linear Regression with Gradient Descent](https://blog.devgenius.io/linear-regression-using-gradient-descent-in-python-f75b7233ed1c) 📝
- [Polynomial Regression with Gradient Descent](https://towardsdatascience.com/polynomial-regression-gradient-descent-from-scratch-27db2336fe9) 📖

---

⭐ **Star this repository** if you find it useful! Contributions and feedback are welcome! 😊