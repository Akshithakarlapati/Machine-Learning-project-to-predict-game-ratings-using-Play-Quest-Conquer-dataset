# 🎮 Machine Learning Project: Game Rating Prediction

## 📌 Project Overview
This project focuses on analyzing and predicting game ratings for an online gaming platform, **Play Quest Conquer (PQC)**. The platform offers a wide range of games where users can browse, purchase, play, trade, and interact with other players.

The main objective is to build a **machine learning model** that identifies key factors influencing game ratings and accurately predicts the **Average Rating** of games.

---

## 🎯 Objectives
- Analyze game-related data to extract meaningful insights  
- Identify factors influencing game ratings  
- Build and evaluate machine learning models for prediction  
- Provide data-driven recommendations to improve user satisfaction and engagement  

---

## 📊 Dataset Description
The dataset includes various features related to games, such as:
- Game Type (Base / Premium)  
- Release Year  
- Age Category  
- Minimum & Maximum Players  
- Average Play Time  
- Game Complexity  
- User engagement metrics (owners, traders, interests)  
- Average Rating (target variable)  

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights from data exploration include:

- Majority of games are **Base Games**, indicating dataset imbalance  
- Most games fall under **12 to under 18 age category**  
- Average playtime shows **outliers and right-skewed distribution**  
- Weak positive relationship between:
  - Playtime and Rating  
  - Complexity and Rating  
- Strong correlations exist among engagement-related features (owners, traders, interests)  
- Average ratings are mostly concentrated between **6 and 8** :contentReference[oaicite:0]{index=0}  

---

## ⚙️ Data Preprocessing
- Handling missing values  
- Removing or treating outliers  
- Encoding categorical variables  
- Feature scaling and normalization  

---

## 🤖 Machine Learning Models
The following models were implemented and compared:
- Linear Regression  
- Decision Tree  
- Random Forest  

### ✅ Final Model:
**Random Forest** was selected due to:
- Higher accuracy  
- Ability to capture complex relationships  
- Robust performance with mixed data types :contentReference[oaicite:1]{index=1}  

---

## 📈 Evaluation Metrics
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- R² Score  

These metrics were used to evaluate model performance and prediction accuracy.

---

## 🚀 Key Insights
- Game ratings are influenced more by **engagement factors** than basic configurations  
- Complexity and playtime have **moderate impact** on ratings  
- Popular games (more owners/interests) tend to perform better  
- Data imbalance and weak correlations highlight the need for advanced models  

---

## 💡 Recommendations
- Focus on developing games with features that increase user engagement  
- Use predictive models to promote high-potential games  
- Improve data collection and quality for better predictions  
- Personalize user recommendations based on predicted ratings :contentReference[oaicite:2]{index=2}  

---

## 🏆 Project Outcome
The developed machine learning model provides a **scalable and data-driven solution** for predicting game ratings, helping improve decision-making in game development, acquisition, and marketing strategies.

---

## 🔧 Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📌 Future Improvements
- Hyperparameter tuning  
- Feature engineering  
- Trying advanced models (XGBoost, Gradient Boosting)  
- Deployment as a web application  

---
