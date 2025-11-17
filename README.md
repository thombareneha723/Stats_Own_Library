# 📊 Stats_Own_Library  
A custom Python statistics library implemented using OOP concepts.

This project contains a user-built statistics module that performs essential descriptive statistics, distribution checks, confidence intervals, empirical rule calculations, outlier detection, and visualizations — all wrapped inside a clean, object-oriented class.

---

## 📁 Project Structure
Stats_Own_Library/
│── Stats_OOP.py
│── README.md
│── requirements.txt


---

## ✨ Features

### ✔ Basic Statistics
- Total / Count  
- Minimum / Maximum  
- Range  
- Mean, Median  
- Mode  
- Variance & Standard Deviation  

### ✔ Distribution & Normality
- Skewness  
- Kurtosis  
- Shapiro–Wilk Test  

### ✔ Quartile-Based Calculations
- Q1, Q3  
- IQR  
- Lower & Upper Whiskers  
- Outlier Count  

### ✔ Confidence Intervals
- 95%  
- 97%  
- 99%  

### ✔ Empirical Rule (68-95-99.7)

### ✔ Automatic Visualizations
- Histogram + KDE  
- Boxplot  
- Countplot  
- Pie chart  

---

## 🚀 How to Use

```python
from Stats_OOP import Statistics_test

# Sample data
data = [10, 20, 30, 40, 50, 60, 70]

# Create object
obj = Statistics_test(data)

# Call any function
obj.average()
obj.var()
obj.visualize()

# Or run all functions at once
obj.everything()

_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _  _

📦 Installation
pip install -r requirements.txt


