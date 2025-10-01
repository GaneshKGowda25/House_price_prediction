# 🏠 House Price Prediction Using Linear Regression (Scikit-Learn)  

![House Price](https://img.shields.io/badge/Project-House%20Price%20Prediction-blue?style=flat-square)  
![Python](https://img.shields.io/badge/Python-3.11-blue?style=flat-square&logo=python)  
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-0.24-green?style=flat-square)  

---

## 📌 Project Overview

**House Price Prediction** is a Machine Learning project that uses **Linear Regression** to predict housing prices based on various features using **Scikit-Learn**.  

This project includes:  
- Data analysis and visualization  
- Outlier removal  
- Feature transformation  
- Model training and evaluation  
- Interactive prediction interface  

💡 This project is designed for **students, ML enthusiasts, and recruiters** to understand a practical implementation of linear regression.

---

## 📂 Dataset

The dataset is loaded from `Housing.csv` and contains:  

| Feature           | Description                             |
|-------------------|-----------------------------------------|
| price             | House price                            |
| area              | Area in square feet                    |
| bedrooms          | Number of bedrooms                     |
| bathrooms         | Number of bathrooms                    |
| stories           | Number of stories                      |
| mainroad          | Whether house is near main road       |
| guestroom         | Whether there is a guest room         |
| basement          | Whether there is a basement           |
| hotwaterheating   | Hot water heating availability         |
| airconditioning   | Air conditioning availability          |
| parking           | Number of parking spaces               |
| prefarea          | Preferred area location                |
| furnishingstatus  | Furnishing status                      |

---

## 🛠 How It Works  

1. **Data Loading**: Import `Housing.csv`  
2. **Data Analysis**: Check null values, visualize features  
3. **Outlier Removal**: Using Interquartile Range (IQR)  
4. **Data Transformation**: Standard scaling & one-hot encoding  
5. **Train/Test Split**: Split dataset into training and testing  
6. **Model Building**: Train Linear Regression model  
7. **Evaluation**: MAE, RMSE, R² score  
8. **Interactive Prediction**: Input custom house details for prediction  

---

## 📊 Evaluation Metrics

| Metric      | Value         |
|-------------|---------------|
| MAE         | ~780,407      |
| RMSE        | ~1,069,842    |
| R² Score    | ~0.72         |

---

## 🔍 Sample Feature Insights  

- **Area vs Price**: Larger areas generally lead to higher prices.  
- **Bedrooms & Bathrooms**: Additional bedrooms and bathrooms increase price marginally.  
- **Stories**: Multi-story houses often have higher value.  
- **Parking**: Availability of parking positively impacts price.  

*(Plots for these insights can be found in the notebook.)*

---

## 🎯 Interactive Prediction  

Run the notebook and use the function to enter custom values:  

```python
predict_from_input(model, preprocessor)
