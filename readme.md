# Coffee Sales Data Analysis ☕

This repository contains a detailed exploratory data analysis (EDA) of a coffee sales dataset. The analysis explores sales trends over months, weekdays, hours, and coffee types, uncovering insights into customer behavior and product popularity.

---

## 📋 Dataset

The dataset is sourced from Kaggle:  
[navjotkaushal/coffee-sales-dataset](https://www.kaggle.com/datasets/navjotkaushal/coffee-sales-dataset)

It contains sales records including timestamps, coffee types, prices, and other relevant details.

---

## 🔧 Libraries Used

- `numpy`  
- `pandas`  
- `matplotlib`  
- `seaborn`  
- `kaggle` API for downloading dataset  

---

## 🧹 Data Cleaning Steps

- Column names were standardized (lowercase and stripped of whitespace)  
- Removed the `cash_type` column since it had only one unique value  
- Checked for missing values and duplicates (none found)  

---

## 📊 Analysis & Visualizations

### Monthly Sales Trend
- Visualized total sales count by month  
- **Insight:** March has the highest sales count, while April has the least.

### Weekday Sales Trend
- Visualized sales count by weekday  
- **Insight:** Tuesday has the most sales; Sunday has the least, likely due to being a holiday.

### Hourly Sales Trend
- Sales distribution over hours of the day  
- **Insight:** Peak sales occur around 10 AM, coinciding with office hours.

### Coffee Popularity
- Bar plot showing the number of orders per coffee type  
- **Insight:** "Americano With Milk" is the most popular, while "Espresso" is the least.

### Coffee Price Distribution
- Strip plot displaying unique price values for each coffee type  
- Bar plot showing average coffee prices  
- **Insight:** Average prices of "Cocoa," "Cappuccino," "Hot Chocolate," and "Latte" are similar.

### Income from Coffee Types
- Total income generated per coffee type  
- **Insight:** "Latte" generates the highest income, likely due to its price.

---

## 📓 Notebook

You can explore the full analysis in the notebook file:  
[`coffee_sales_analysis.ipynb`](./coffee_sales_analysis.ipynb)  

Open it using Jupyter Notebook, JupyterLab, or VS Code to run and interact with the code.

---

## 🔗 Links

- [Kaggle Dataset](https://www.kaggle.com/datasets/navjotkaushal/coffee-sales-dataset)  
- [Kaggle API Documentation](https://www.kaggle.com/docs/api)

---

## Requirements

Make sure you have the following Python libraries installed:

- numpy  
- pandas  
- matplotlib  
- seaborn  
- kaggle (for dataset download)

You can install them with:

```bash
pip install numpy pandas matplotlib seaborn kaggle
