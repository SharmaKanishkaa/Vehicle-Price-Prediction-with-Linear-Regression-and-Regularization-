# 🚗 Vehicle Price Prediction with Linear Regression  

Welcome to the **Vehicle Price Prediction Project**! This project explores the **CarDekho Vehicle Dataset** to predict the selling price of vehicles using **Linear Regression** and its regularized variants.  

---

## 📋 **Dataset Overview**  

The dataset provides detailed information about used vehicles, including their attributes and historical prices.  

### **Columns**  

| **Feature**          | **Description** |  
|-----------------------|-----------------|  
| `Car_Name`           | Name of the car model. |  
| `Year`               | Year of manufacturing. |  
| `Selling_Price`      | Price the car was sold for (target variable). |  
| `Present_Price`      | Current ex-showroom price of the car. |  
| `Kms_Driven`         | Total kilometers driven by the vehicle. |  
| `Fuel_Type`          | Type of fuel used (Petrol/Diesel/CNG). |  
| `Seller_Type`        | Whether the seller is a dealer or an individual. |  
| `Transmission`       | Transmission type (Manual/Automatic). |  
| `Owner`              | Number of previous owners. |  

---

## 📊 **Workflow**  

1. **Exploratory Data Analysis (EDA):**  
   - Visualized trends between features like `Present_Price`, `Year`, and `Selling_Price`.  
   - Discovered relationships between car specifications and price.  

2. **Linear Regression:**  
   - Implemented **Linear Regression from scratch** to predict the selling price.  
   - Achieved an **R² score of 88%**.  

3. **Regularization Techniques:**  
   - Applied **Lasso, Ridge, and ElasticNet** regression to handle potential overfitting and feature importance.  
   - **Performance Comparison:**  
     | Model       | R² Score |  
     |-------------|----------|  
     | Linear Regression | **88%** |  
     | Lasso             | 84%     |  
     | Ridge             | 85%     |  
     | ElasticNet        | 80%     |  

---

## 🎯 **Results**  

- Linear Regression provided a strong baseline with **88% accuracy** in predicting prices.  
- Regularization techniques slightly reduced the R² scores, showcasing their ability to handle overfitting in complex datasets.  

---

## 🛠️ **Tools and Techniques**  

- **Libraries Used:** `pandas`, `NumPy`, `Matplotlib`, `seaborn`, `scikit-learn`  
- **Modeling Approaches:**  
  - Linear Regression (from scratch)  
  - Regularized Models: Lasso, Ridge, ElasticNet  

---

## ✨ **Key Takeaways**  

- Linear Regression performed well with minimal preprocessing, indicating strong feature correlations in the dataset.  
- Regularization techniques like **Ridge** and **Lasso** improved model robustness by penalizing feature weights.  
- The dataset is ideal for exploring **feature importance**, **regularization**, and regression modeling concepts.  
