# Superstore Sales Analytics 🛒

An Exploratory Data Analysis (EDA) project focusing on retail sales trends and categorical performance to extract actionable business insights from raw transaction records.

**Overview**
This repository contains a Jupyter Notebook that analyzes a retail dataset (`Superstore.csv`)[cite: 1]. The goal of this project is to demonstrate end-to-end data manipulation and interactive data visualization using Python. By breaking down sales by time and category, the analysis highlights revenue drivers and seasonal purchasing patterns.

**Key Features & Insights**
* **Time-Series Extraction:** Cleaned and engineered date columns into distinct Order Month, Year, and Day of Week features for deeper temporal analysis.
* **Monthly Revenue Tracking:** Developed interactive Plotly line charts with customized currency labels to track month-over-month sales performance.
* **Categorical Breakdown:** Visualized the revenue distribution across major product groups (Furniture, Office Supplies, Technology) using formatted Plotly pie charts.
<h2>KPI's Addresssed</h2>
<a href="">SUPERSTORE IMAGES</a>
*Sales by Month**
<img src ="Sales by Month(superstore).png">
<img src ="Sales by Month2(superstore).png">
*Sales by Category**
<img src ="Sales by Category(superstore).png">
*Sales by Sub-Category**
<img src ="Sales by Sub-category(superstore).png">
*Sales vs Profit**
<img src ="Sales vs Profit(superstore).png">
*Sales vs Profit Ratio**
<img src ="Sales vs Profit ratio(superstore).png">

**Tech Stack**
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `plotly.express`, `plotly.graph_objects`, `seaborn`, `matplotlib`

**How to Use**
1. Clone the repository:
   `git clone https://github.com/yourusername/superstore-sales-eda.git`
2. Ensure you have the required libraries installed:
   `pip install pandas numpy matplotlib seaborn plotly`
3. Open the Jupyter Notebook to interact with the visualizations and explore the data.
