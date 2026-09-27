# Task 10 – Comparative Insights

## PlaceMux Phase 1 Industry Immersion – Data Analyst

### 📌 Project Overview

This project is part of the **PlaceMux Phase 1 Industry Immersion Program – Task 10: Comparative Insights**.

The objective of this task is to compare different business segments and identify the factors driving differences in sales performance.

Instead of looking only at overall totals, the analysis compares categories, sales channels, order statuses, and cross-segment performance to understand **who is performing differently and why**.

---

## 🎯 Objective

The main objectives of this analysis are:

* Compare performance across meaningful business segments.
* Compare sales and order contributions.
* Normalise comparisons for segment size.
* Identify the segments driving overall results.
* Analyse category and sales-channel interactions.
* Check for reversing sub-trends and Simpson's paradox.
* Generate actionable comparative insights.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* GitHub

---

## 📊 Analysis Performed

### 1. Category Comparison

Compared:

* Clothing
* Electronics
* Grocery
* Home

Metrics analysed:

* Total Net Sales
* Total Orders
* Total Quantity
* Average Sales per Order
* Sales Share
* Order Share

### 2. Sales Channel Comparison

Compared:

* Online
* Offline

The analysis examined sales contribution, order contribution, quantity and average sales per order.

### 3. Order Status Comparison

Compared:

* Completed
* Pending
* Cancelled

This helped understand how sales and orders are distributed across different order outcomes.

### 4. Category × Sales Channel Analysis

A cross-segment comparison was performed to examine category performance across Online and Offline channels.

### 5. Driver Analysis

The analysis separated:

* **Order Volume Effect**
* **Sales Value per Order Effect**

This helped identify why a category with more orders may not necessarily generate the highest sales.

### 6. Simpson's Paradox Check

Cross-segment comparisons were used to check whether an overall pattern could change when the data was divided into smaller groups.

---

## 🔍 Key Comparative Insights

* **Clothing** generated the highest net sales among the analysed categories.
* Clothing's sales contribution was higher than its share of total orders, indicating relatively higher sales value per order.
* **Grocery** had the highest number of orders but the lowest average sales per order.
* **Online** contributed a larger share of total net sales than Offline.
* Online sales share was **63.6%**, compared with **36.4%** for Offline.
* The analysis demonstrated that **order volume alone does not explain overall sales performance**.
* Category mix, sales channel and average sales per order all contribute to differences in performance.

---

## 📈 Visualisations

The project includes comparative visualisations for:

1. Category Sales Share vs Order Share
2. Sales Channel Sales Share vs Order Share
3. Order Status Sales Share vs Order Share
4. Category × Sales Channel Net Sales

---

## 📁 Project Structure

```text
Task_10_Comparative_Insights/
│
├── Task_10_Comparative_Insights.ipynb
├── Task_8_Cleaned_Retail_Sales.csv
└── README.md
```

---

## ✅ Conclusion

Task 10 demonstrates how comparative analysis can provide deeper insights than overall totals.

The analysis shows that differences in sales performance are influenced by **category mix, order volume, average sales per order, sales channel and order status**.

This comparative approach helps identify the segments that contribute most to overall business performance and provides a stronger foundation for data-driven decision-making.

---

## 🎓 Learning Outcomes

Through this task, I strengthened my skills in:

* Pandas `groupby()`
* Pivot tables
* Data aggregation
* Comparative analysis
* Percentage/share calculations
* Data visualisation with Seaborn
* Segment-level analysis
* Driver identification
* Simpson's paradox verification
* Business insight generation

---

### Project

**PlaceMux Phase 1 Industry Immersion – Task 10**

**Topic:** Comparative Insights

**Role:** Data Analyst

