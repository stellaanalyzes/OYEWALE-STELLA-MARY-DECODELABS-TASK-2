# E-Commerce Orders — Exploratory Data Analysis (EDA)

For Task 2 of my internship, I explored the cleaned e-commerce orders dataset using Microsoft Excel. I calculated key statistics — count, mean, median, minimum, and maximum — across the total price and unit price columns to better understand how the data is distributed and spot any patterns worth noting.

---

##  Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Analysis Performed](#analysis-performed)
- [Key Statistics](#key-statistics)
- [Screenshots](#screenshots)
- [Tools Used](#tools-used)
- [Key Takeaways](#key-takeaways)

---

##  Project Overview

This project covers the exploratory data analysis phase of a cleaned e-commerce sales orders dataset, completed as Task 2 of my data analytics internship. Building on the cleaned dataset from Task 1, this task involved computing descriptive statistics across numerical columns to summarise the data, identify patterns, and draw early observations about pricing and order behaviour.

---

##  Dataset

The dataset used is the cleaned e-commerce orders table produced in Task 1, consisting of 13 columns spanning order details, customer information, product data, pricing, payment methods, order statuses, and referral sources.

---

##  Analysis Performed

### 1. Descriptive Statistics
Computed the following metrics across the `Total Price` and `Unit Price` columns:
- **Count** — total number of valid records
- **Median** — middle value of the distribution
- **Mean** — average value across all records
- **Maximum** — highest recorded value
- **Minimum** — lowest recorded value

### 2. Pattern Observation
Reviewed the computed statistics to identify the spread of pricing values, spot potential outliers, and note the difference between median and mean as an indicator of data skew.

---

##  Key Statistics

| Metric | Total Price | Unit Price |
|---|---|---|
| Count | 1,200 | 1,200 |
| Median | 823.6 | 364.2 |
| Mean | 1,054.0 | 356.4 |
| Maximum | 3,456.4 | 699.9 |
| Minimum | 11.4 | 11.4 |

---

##  Screenshots

### Cleaned Data
![Cleaned Data](cleaned-data-screenshot.png)

### Key Insights
![Key Insights](key-insights-screenshot.png)

---

##  Tools Used

- Microsoft Excel

---

##  Key Takeaways

- The mean total price (1,054.0) is noticeably higher than the median (823.6), suggesting the distribution is right-skewed — a small number of high-value orders are pulling the average up.
- Unit price values range from 11.4 to 699.9, indicating a wide variety of products at very different price points.
- With 1,200 records across both columns, the dataset is complete with no missing values in the numerical fields.
- Exploratory analysis at this stage helps set the direction for deeper analysis and informed decision-making.
