# 🥕 Good Food Purchasing Data Analysis

📌 **Government Food Purchasing Trends Across Agencies**

➡️ This project analyzes the **Good Food Purchasing Data**, which tracks food procurement by various city agencies in the U.S., promoting transparency in public food spending and encouraging sustainable, equitable food systems.

---

## 📁 Dataset

The dataset is sourced from the **U.S. Government Open Data Portal**:  
[https://catalog.data.gov/dataset/good-food-purchasing-data](https://catalog.data.gov/dataset/good-food-purchasing-data)

It contains details such as:
- Product name, category, and group  
- Quantity purchased and total cost  
- Vendors and city agencies  
- Unit price, product origin, and time period

---

## 🎯 Project Objectives

1. **Analyze the distribution of food spending across different food categories**  
2. **Compare the average price per unit of key food items across different City agencies**  
3. **Identify and visualize the top food items and vendors based on quantity and cost**  
4. **Track year-over-year changes in fruit and vegetable purchases**  
5. **Detect food items with significant price fluctuations over time**  
6. **Classify food items into processed vs. whole foods and analyze their purchase ratio**  
7. **Explore vendor diversification across product categories**

---

## 🧼 Data Cleaning

Before analysis, the dataset was cleaned for accuracy:
- Handled missing values (especially in price and time fields)
- Parsed and standardized date formats
- Removed duplicates and inconsistent vendor/product entries
- Created new features (like `Year`, `Food Type` classification)

---

## 📊 Exploratory Data Analysis (EDA)

To derive insights and visualize trends, the following techniques were used:
- Bar charts, pie charts, and heatmaps
- Grouped aggregations and trend lines
- Outlier detection (boxplots)
- Correlation matrix for numerical features
- Time-series analysis by year

---

## 🛠️ Libraries Used

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `datetime`

---

## 🔍 Key Insights

- **Spending was highly concentrated** in specific categories like grains and dairy.
- **Price per unit varied widely** across city agencies for the same food items.
- **Top vendors** were responsible for large shares of total food cost.
- **Fruit and vegetable purchases** fluctuated over years, possibly due to policy changes.
- **Certain products like ketchup and chips showed price volatility** over time.
- **Whole foods made up a larger portion of purchases**, but processed food spending was significant.
- **Many vendors specialized**, but a few served across diverse categories.

---

## 🌍 Why This Project Matters

Understanding public food procurement patterns helps governments:
- Improve **budget efficiency**  
- Support **local and sustainable** vendors  
- Encourage **healthy food choices**  
- Make **data-driven policy decisions** to strengthen food systems

This project aims to turn raw data into actionable insights for better governance and transparency.

---

## 🔭 Future Scope

- **Forecast spending trends** with machine learning  
- **Cluster vendors** by product diversity and price patterns  
- **Develop an interactive dashboard** for city officials and public use  
- **Geo-map vendor origins** to analyze local vs. global sourcing  

---

## 🤝 Let’s Connect!

Have ideas to enhance this project or want to collaborate on public data transparency projects?  
Feel free to **fork the repo**, raise an issue, or reach out!
