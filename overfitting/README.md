# Understanding Overfitting in Regression Models

This project demonstrates the concept of **overfitting** in machine learning, particularly within **regression models**. It uses synthetic student performance data to illustrate how different modeling techniques behave with varying levels of model complexity.

## 📁 Project Files

- `Fit_Overfitting.ipynb`: Jupyter Notebook illustrating the concept with visualizations and model comparisons.
- `student_performance_with_noise.csv`: Dataset used (must be placed in the same directory).

## 📊 Techniques Covered

- Simple Linear Regression
- Ridge Regression
- Lasso Regression
- Polynomial Regression (to simulate overfitting)
- Feature selection using `SelectKBest`

## 📈 Metrics Used

- Mean Squared Error (MSE)
- R² Score
- Cross-validation scores

## 📦 Requirements

Install the following libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
