# 🏠 House Price Prediction Using Linear Regression (Scikit-Learn)

A **Machine Learning project** that predicts house prices based on real-world features using **Linear Regression** implemented with **Scikit-Learn**.  
Includes:  
- Data preprocessing  
- Outlier removal  
- Feature transformation  
- Model training & evaluation  
- Interactive input for custom predictions  

---

## 📜 Table of Contents

1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)  
3. [How It Works](#how-it-works)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Evaluation Metrics](#evaluation-metrics)  
7. [Visualization](#visualization)  
8. [Interactive Prediction](#interactive-prediction)  
9. [Contributing](#contributing)  
10. [Contact](#contact)  

---

## 📌 Project Overview

This project uses **Linear Regression** to predict house prices based on various features such as area, bedrooms, bathrooms, stories, parking spaces, and amenities.  

The model pipeline includes:
- Loading & cleaning dataset  
- Removing outliers  
- Splitting dataset into training and test sets  
- Scaling numerical features  
- Encoding categorical features  
- Training the model  
- Evaluating model performance  
- Interactive prediction for custom inputs  

---

## 📂 Dataset

The dataset is loaded from `Housing.csv` and contains features like:  

| Feature           | Description                             |
|-------------------|-----------------------------------------|
| price             | House price                            |
| area              | Area of the house in square feet      |
| bedrooms          | Number of bedrooms                     |
| bathrooms         | Number of bathrooms                    |
| stories           | Number of stories                      |
| mainroad          | Whether house is near main road       |
| guestroom         | Whether there is a guest room         |
| basement          | Whether there is a basement           |
| hotwaterheating   | Hot water heating available            |
| airconditioning   | Air conditioning available             |
| parking           | Number of parking spaces               |
| prefarea          | Preferred area location                |
| furnishingstatus  | Furnishing status                      |

---

## ⚙ How It Works

The workflow of the project:
1. **Load and inspect the dataset**  
2. **Remove outliers** using Interquartile Range (IQR) method  
3. **Split the dataset** into training and testing sets  
4. **Preprocess data** using StandardScaler and OneHotEncoder  
5. **Train Linear Regression model** using Scikit-learn pipeline  
6. **Evaluate model performance** using MAE, RMSE, and R² score  
7. **Visualize results** with scatter plots and error plots  
8. **Predict house price** interactively based on user input  

---

## 🛠 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/House-Price-Prediction.git
cd House-Price-Prediction
pip install -r requirements.txt
