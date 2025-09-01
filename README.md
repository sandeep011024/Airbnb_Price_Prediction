# Airbnb Price Prediction

This project focuses on predicting Airbnb listing prices using machine learning techniques.  
The goal is to build a model that helps hosts and users estimate fair prices based on various listing features such as location, room type, number of reviews, and availability.

## 📊 Project Overview
- Collected and preprocessed Airbnb dataset
- Performed Exploratory Data Analysis (EDA) to identify pricing patterns
- Engineered meaningful features (location-based, availability, reviews, etc.)
- Built and compared multiple regression models (Linear Regression, Random Forest, XGBoost)
- Tuned hyperparameters for improved accuracy

## 🛠 Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, XGBoost

## 🚀 Results
- Achieved **R² score of 0.87**
- Identified key price drivers: location, property type, and number of reviews
- Visualized feature importance for better interpretability

## 📂 Files
- `Airbnb_Price_Prediction.ipynb` → Jupyter notebook with code & analysis
- `README.md` → Project overview and documentation
- `data/` → Dataset (or link to dataset)

## 📌 Future Improvements
- Deploy the model using Streamlit for interactive price predictions
- Incorporate NLP on reviews to extract sentiment as a pricing factor
