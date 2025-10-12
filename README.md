# 🏠 End-to-End Machine Learning Project  
## House Price Prediction (Regression Problem)

### 📘 Project Overview
This project demonstrates a complete **end-to-end machine learning workflow** — from data loading and preprocessing to model training, evaluation, and deployment.  
The goal is to **predict house prices** based on various features using regression techniques.

---

### 🚀 Key Steps in the Project
1. **Data Collection**
   - Loaded the **California Housing Dataset** (from Aurelien Géron’s “Hands-On Machine Learning” book).
   - Explored key features like median income, location, and population.

2. **Data Exploration & Visualization**
   - Used `pandas`, `matplotlib`, and `seaborn` for EDA.
   - Identified correlations between features and the target variable (`median_house_value`).

3. **Data Preprocessing**
   - Handled missing values and outliers.
   - Created new features (e.g., income category for stratified sampling).
   - Performed one-hot encoding and feature scaling using `StandardScaler`.

4. **Model Training**
   - Trained multiple regression models:
     - Linear Regression  
     - Decision Tree Regressor  
     - Random Forest Regressor
   - Used **GridSearchCV** for hyperparameter tuning.

5. **Model Evaluation**
   - Compared models using RMSE (Root Mean Squared Error).
   - Evaluated final model on the test set.

6. **Deployment (Optional)**
   - Prepared the model for deployment with `joblib` or `pickle`.

---

### 🧠 Tech Stack
| Category | Tools/Libraries |
|-----------|----------------|
| Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Model Persistence | Joblib/Pickle |
| Version Control | Git, GitHub |

