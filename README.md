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

---

Conclusion

What we predicted

We predicted whether a product on iHerb Kazakhstan falls into High Demand or Low Demand based on its price, discount, rating, number of reviews, and engineered features.

What we found

The tuned Random Forest classifier achieved the best performance.

Accuracy : 0.750

ROC-AUC : 0.746

The most important features driving high demand were:

Number of review: 0.417
Price(tenge): 0.205
Old price(tenge): 0.199*.
Logistic Regression served as a useful baseline — if Random Forest only slightly outperforms it, the relationship between features and demand is fairly linear.

Business insights

Discount is a demand driver — products with higher discounts tend to show higher short-term sales, suggesting price sensitivity among iHerb KZ customers.
Rating and reviews matter — highly-rated, well-reviewed products are more likely to be in the high-demand group, confirming that social proof drives purchases.
Price alone is not enough — the feature importance chart shows that raw price is less predictive than discount percentage, meaning customers respond more to perceived savings than absolute price.
Limitations

The Sold data is a short-term snapshot (products recently bought), not total sales history.
Data was collected from the iHerb Kazakhstan specials/discount page only — results may not generalize to full-price products.
A larger dataset collected over multiple time periods would improve model stability.
