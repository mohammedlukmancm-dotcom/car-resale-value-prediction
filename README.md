# car-resale-value-prediction
Machine learning project to estimate second-hand car prices using regression techniques, data preprocessing, and feature engineering.
🚘 Car Resale Value Prediction using Machine Learning

📌 Introduction

Pricing a used car correctly is a common challenge in the automobile market. Many factors influence a car’s resale value, including its age, usage, and condition. This project uses Machine Learning (Multiple Linear Regression) to predict the resale value of cars based on historical data.

---

🎯 Goal of the Project

- Build a predictive model for used car prices
- Understand key factors affecting resale value
- Apply data preprocessing and regression techniques

---

📊 About the Dataset

The dataset consists of car-related attributes such as:

- Year of manufacture
- Current market price
- Distance driven (in km)
- Fuel type (Petrol/Diesel/CNG)
- Seller type (Dealer/Individual)
- Transmission type
- Number of previous owners

Target Variable:

- "Selling_Price"

---

🛠️ Tools & Libraries

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

🔍 Project Steps

Data Understanding

- Loaded and inspected dataset
- Checked structure, types, and summary statistics

Data Cleaning & Preparation

- Converted year into car age
- Removed irrelevant column ("Car_Name")
- Transformed categorical data using encoding

Exploratory Data Analysis

- Pairplot for feature relationships
- Correlation heatmap for insights

Feature Engineering

- Selected important variables
- Separated features (X) and target (y)

Scaling

- Applied StandardScaler for normalization

Model Training

- Used Linear Regression algorithm
- Trained model on training dataset

Model Evaluation

- Evaluated using:
  - Mean Squared Error (MSE)
  - R² Score

---

📈 Performance

- R² Score: ~0.83
- Model shows good prediction capability
- Strong predictors:
  - Present Price
  - Age of the Car

---

📊 Visualizations

- Actual vs Predicted scatter plot
- Comparison line graph for predictions

---

🧠 What This Project Demonstrates

- Real-world regression problem solving
- Data preprocessing techniques
- Handling categorical variables
- Model evaluation and interpretation

---

📁 Project Files

├── car_data.csv
├── car_price_prediction.ipynb
├── README.md

---

▶️ How to Use

1. Clone the repository

git clone https://github.com/your-username/car-resale-value-prediction.git

2. Install required libraries

pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the Jupyter Notebook

jupyter notebook

---

🚀 Future Scope

- Try advanced regression models
- Improve accuracy with feature selection
- Deploy as a web application
- Add user input prediction interface

---

📌 Conclusion

This project demonstrates how machine learning can be used to estimate used car prices effectively, helping users make informed financial decisions.

---

👨‍💻 Author

Mohammed Lukman CM
