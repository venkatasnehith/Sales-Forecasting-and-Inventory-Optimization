# Sales-Forecasting-and-Inventory-Optimization
This repository  performs exploratory data analysis (EDA) on weekly sales data, applies ARIMA forecasting, and implements basic inventory optimization techniques including EOQ (Economic Order Quantity) and Reorder Point calculation
---

# 📈 Sales Forecasting and 📦 Inventory Optimization

This repository contains a Jupyter notebook that performs **exploratory data analysis (EDA)** on weekly sales data, applies **ARIMA forecasting**, and implements basic **inventory optimization** techniques including **EOQ (Economic Order Quantity)** and **Reorder Point** calculation.

---

## 📊 Dataset

The dataset contains **weekly sales data** for multiple stores and includes the following fields:

* `Store`: Store ID
* `Date`: Weekly date
* `Weekly_Sales`: Sales amount
* `Holiday_Flag`: Indicates if the week includes a holiday
* `Temperature`: Weekly average temperature
* `Fuel_Price`: Fuel price
* `CPI`: Consumer Price Index
* `Unemployment`: Unemployment rate

---

## 🔍 Analysis Performed

### 1. **Environment Setup**

* Installs and imports libraries like `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scikit-learn`, `xgboost`.

### 2. **Data Loading and Cleaning**

* Manual CSV upload (for Google Colab)
* Inspect columns, datatypes, and check for nulls

### 3. **Exploratory Data Analysis (EDA)**

* Converts `Date` column to datetime and sorts data
* Plots:

  * Total weekly sales
  * Monthly & yearly trends
  * Store-level sales
* Adds rolling mean lines for trend visualization

### 4. **Sales Forecasting**

* Resamples weekly data to monthly/weekly
* Builds an ARIMA model for time series forecasting
* Plots historical vs. forecasted sales

### 5. **Inventory Optimization**

* Calculates EOQ: Optimal order size based on demand, ordering, and holding cost
* Calculates Reorder Point: When to place the next order based on lead time and daily demand

---

## 🚀 How to Use

1. Clone this repo or open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload your dataset (CSV)
3. Run all cells in order
4. Visualize results and interpret EOQ & reorder point values

---

## 📁 Files Included

* `your_notebook_name.ipynb`: Main Jupyter Notebook
* `archive (2).zip`: Contains the dataset (replace with your actual filename)
data set link-------->https://drive.google.com/file/d/1FWU2gVz-06mwXxxKIaGCQKnfZAXDEldP/view?usp=sharing
---

## 📦 Dependencies

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `statsmodels`
* `scikit-learn`
* `xgboost`

---

## 💡 Future Improvements

* Add advanced models (Prophet, XGBoost regression)
* Include safety stock and service level in inventory optimization
* Perform product-level or department-level forecasting
* Create an interactive dashboard with Streamlit or Gradio

---
