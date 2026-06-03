# E-Commerce Orders — Exploratory Data Analysis (EDA)

For Task 2 of my internship, I explored the cleaned e-commerce orders dataset using Microsoft Excel. I calculated key statistics — count, mean, median, minimum, and maximum — across four numerical columns to better understand how the data is distributed and spot any patterns worth noting.

---

##  Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Analysis Performed](#analysis-performed)
- [Key Statistics](#key-statistics)
- [Key Insights](#key-insights)
- [Screenshots](#screenshots)
- [Tools Used](#tools-used)
- [Key Takeaways](#key-takeaways)

---

##  Project Overview

This project covers the exploratory data analysis phase of a cleaned e-commerce sales orders dataset, completed as Task 2 of my data analytics internship. Building on the cleaned dataset from Task 1, this task involved computing descriptive statistics across all numerical columns to summarise the data, identify patterns, and draw early observations about pricing, quantity, and cart behaviour.

---

##  Dataset

The dataset used is the cleaned e-commerce orders table produced in Task 1, consisting of 13 columns spanning order details, customer information, product data, pricing, payment methods, order statuses, and referral sources. The four numerical columns analysed in this task are `Total Price`, `Unit Price`, `Quantity`, and `Items in Cart`.

---

##  Analysis Performed

### 1. Descriptive Statistics
Computed the following metrics across all four numerical columns:
- **Count** — total number of valid records
- **Median** — middle value of the distribution
- **Mean** — average value across all records
- **Maximum** — highest recorded value
- **Minimum** — lowest recorded value

### 2. Pattern Observation
Reviewed the computed statistics to identify the spread of values, spot potential outliers, and note differences between mean and median as indicators of data skew across each column.

---

##  Key Statistics

| Metric | Total Price | Unit Price | Quantity | Items in Cart |
|---|---|---|---|---|
| Count | 1,200 | 1,200 | 1,200 | 1,200 |
| Median | 823.6 | 364.2 | 3 | 5.00 |
| Mean | 1,054.0 | 356.4 | 2.9 | 5 |
| Maximum | 3,456.4 | 699.9 | 5 | 10 |
| Minimum | 11.4 | 11.4 | 1 | 1 |

---

##  Key Insights

- **Total Price** — The mean ($1,054) is significantly higher than the median ($823.60), meaning the average order value is being pulled up by a small number of high-value purchases. The wide range from $11.40 to $3,456.40 confirms that a few large orders are skewing the distribution to the right.
- **Unit Price** — The mean ($356.40) and median ($364.20) are very close, suggesting unit prices are more evenly distributed across the dataset. Values range from $11.40 to $699.90.
- **Quantity** — The mean (2.9) and median (3) are nearly identical, indicating quantity per order is fairly consistent across customers, with purchases ranging from 1 to 5 items per order.
- **Items in Cart** — The mean and median are both 5, with a minimum of 1 and a maximum of 10. The fact that the average cart size (5) is higher than the average quantity purchased (2.9) suggests customers are browsing and adding more items to their cart than they ultimately buy.
- **Overall** — The most notable finding is the gap between the mean and median for Total Price, which points to a right-skewed distribution driven by high-value outlier transactions. Quantity and Items in Cart are the most normally distributed of the four columns.

---

##  Screenshots

### Descriptive Statistics Table
![Descriptive Statistics](stats-table.jpg)

### Key Insights
![Key Insights](key-insights.png)

---

##  Tools Used

- Microsoft Excel

---

##  Key Takeaways

- A gap between mean and median is a strong signal of skew — in this case, a small number of high-value orders are pulling the Total Price average up.
- Unit prices are more evenly spread, making them more predictable for pricing strategy decisions.
- Customers consistently add more items to their cart than they purchase, which is a useful behavioural insight for cart abandonment analysis.
- Descriptive statistics provide a solid foundation for deeper analysis and data-driven decision making.

