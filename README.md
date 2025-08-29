# Statistics Project: Monthly Expenditure Analysis at ICDS Preschool

## Introduction
This project analyzes the monthly expenditure on vegetables, groceries, and health mix powder for students at a preschool under the **Integrated Child Development Service (ICDS)**. ICDS is a scheme launched in 1975 by the Tamil Nadu Government to improve health, nutrition, and education for children. The aim is to understand spending patterns and estimate future monthly expenditures for better planning.

---

## Data
The dataset contains monthly expenditure information for 2022, collected from ICDS. The data includes:

- **Vegetables**: Monthly expenditure for students at the preschool.
- **Groceries**: Monthly expenditure for students.
- **Health Mix Powder**: Provided based on age (average amount per student).

---

## Methods Applied

### 1. Newton Forward Interpolation
**Objective:** Estimate the average expenditure on vegetables in **February**.  

| Month (x) | 1 | 3 | 5 | 7 | 9 | 11 |
|------------|---|---|---|---|---|---|
| Expenditure (y) | 590.46 | 455.24 | 397.86 | 666.23 | 669.50 | 590.23 |

**Result:**  
The average expenditure in February (x = 2) = **605.46**

---

### 2. Newton Backward Interpolation
**Objective:** Estimate the average expenditure on groceries in **November**.  

| Month (x) | 2 | 4 | 6 | 8 | 10 | 12 |
|------------|---|---|---|---|----|----|
| Expenditure (y) | 221.50 | 246.23 | 123.33 | 191.50 | 222.60 | 226.21 |

**Result:**  
The average expenditure in November (x = 11) = **195.95**

---

### 3. Newton Divided Difference / Lagrange’s Method
**Objective:** Estimate the expenditure for a particular month using the divided difference method.  

| x | 2 | 6 | 18 | 22 |
|---|---|---|---|---|
| y | 165 | 142 | 125 | 50 |

**Result:**  
f(12) = **146.125**

---

## Conclusion
- Every child receives **equal benefits**, and the average expenditure is consistent.
- Experimental analysis helps in **predicting future month expenditure**.
- Applying numerical methods like **Newton Interpolation and Divided Difference** in real-life data provides useful insights for budgeting and planning.

---

## Author
**Yamuna Saravanan**  
Data Science Enthusiast  

---
## Notes
- This project is focused on **numerical methods** and their application in real-world data.
- Data and methods can be extended for **predicting future expenditures** or optimizing budget allocation.
