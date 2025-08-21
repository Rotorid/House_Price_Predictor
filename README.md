# House Price Prediction using Machine Learning

This project predicts **California housing prices** using various regression models.  
It walks through the complete ML workflow — from **data preprocessing** to **model tuning** and **final evaluation**.

---

##  Project Overview
- **Dataset**: California Housing dataset (from Scikit-learn).  
- **Objective**: Predict the median house value based on features such as median income, housing age, population, and number of rooms.  
- **Tech Stack**: Python, Scikit-learn, Pandas, NumPy, Matplotlib.

---

##  Workflow
1. **Data Loading & Exploration**  
   - Checked distributions, correlations, and missing values.  
2. **Data Preprocessing**  
   - Handling missing values, feature scaling, encoding.  
3. **Model Training**  
   - Linear Regression, Decision Tree, Random Forest.  
4. **Evaluation Metrics**  
   - MAE, MSE, RMSE, R², Adjusted R².  
5. **Model Tuning**  
   - RandomizedSearchCV & GridSearchCV for hyperparameter optimization.  
6. **Final Model**  
   - Tuned Random Forest with improved accuracy.  
7. **Visualization**  
   - Predicted vs. Actual scatter plots, residual error plots.  

---

##  Results
- **Best Model**: Tuned Random Forest  
- **R² Score**: ~0.80  
- **MAE**: ~33,000 (average error per house)  
- Outperformed baseline models significantly.

---

##  How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction
