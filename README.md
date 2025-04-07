# 🚗 Car Price Predictor

A machine learning project to predict the prices of used cars using real-world data scraped from Quikr. The goal was to build a regression model that can accurately estimate the selling price of a second-hand car based on features like brand, model, year of manufacture, fuel type, and kilometers driven.

## 📌 Key Highlights
**Dataset Source**: [Quikr Car Listings](https://github.com/rajtilakls2510/car_price_predictor/blob/master/README.md)

Tech Stack: Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Jupyter Notebook

Problem Type: Regression

## 🛠️ What I Did
Cleaned and preprocessed messy data (e.g., handled non-numeric values like "Ask For Price", inconsistent year formats, and text noise in car names).

Extracted relevant features and reduced dimensionality by simplifying car names and brands.

Performed exploratory data analysis (EDA) to find insights into price distribution across companies, fuel types, and usage.

Trained and compared multiple regression models:

Linear Regression, Random Forest, Gradient Boosting, SVM, KNN, Decision Tree

Used Pipelines and OneHotEncoding for streamlined preprocessing.

Evaluated model performance using R² Score, Mean Absolute Error (MAE), and RMSE.

Visualized model performance and selected the best model based on R² Score.

## 📈 Result
The final model achieved a strong R² score and demonstrated consistent performance on the test set. This project serves as a solid foundation for building a used-car price prediction tool or web app.