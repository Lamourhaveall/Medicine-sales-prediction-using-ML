# **Medicine Sales Prediction on iHerb**

**Author:** Makhabbat Khaval  

Predicting daily medicine product sales using machine learning based on product feedback, historical sales, and demand indicators.

---

## **Overview**
This project aims to build a machine learning model to forecast daily sales of medicine products on iHerb. The predictions help businesses:  

- **Forecast demand accurately**  
- **Optimize inventory**  
- **Support data-driven decision making**  

**Workflow includes:**  
1. **Data preprocessing**  
2. **Exploratory Data Analysis (EDA)**  
3. **Feature engineering**  
4. **Model training and evaluation**  
5. **Model comparison**  
6. **Final predictions**

---

## **Dataset Description**
The dataset contains the following features:  

- **Product Name**  
- **Rating**  
- **Number of Reviews**  
- **Price (tenge)**  
- **Old Price (tenge)**  
- **Units Sold**   
- **Discount**  

**Data Cleaning Steps:**  
- **Handling missing values**  
- **Treating outliers**  
- **Encoding categorical variables**

---

## **Tools & Libraries**
- **Python**  
- **pandas**, **numpy**  
- **matplotlib**, **seaborn**  
- **scikit-learn**  
- **Selenium** (for web scraping)

---

## **Machine Learning Methods**

### **Models**
- **Linear Regression** – baseline model  
- **Random Forest Regressor** – captures nonlinear relationships

### **Hyperparameter Tuning**
- **GridSearchCV** – exhaustive parameter search  
- **RandomizedSearchCV** – faster randomized optimization

---

## **Model Performance**
The best-performing model achieved:  

- **MAE:** 0.00593  
- **MSE:** 0.00018  
- **R²:** 0.9298  

This demonstrates **strong predictive performance** and **good model fit**.

---

## **Conclusion**
The project successfully predicts medicine sales with high accuracy, demonstrating the effectiveness of machine learning for demand forecasting and inventory optimization.



