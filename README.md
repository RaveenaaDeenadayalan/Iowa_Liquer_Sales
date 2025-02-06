# Iowa Liquor Sales Analysis

## **Project Overview**
This project analyzes liquor sales trends in Iowa using a 5% sample of the original dataset, which consisted of approximately 29.88 million records over the years (2012 - 2024). The goal was to uncover patterns and insights that could inform business strategies and operational decisions for liquor retailers and distributors.

### Tableau Visualization
[View my Tableau Dashboard here!](https://public.tableau.com/views/IowaLiquerSales/IOWALIQUERSALES?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## **Business Question**
**How have sales trends for different liquor categories evolved over the years in Iowa?**

To answer this question, the analysis focused on sales trends, volume changes, and county-level patterns, along with seasonality and weekly consumption behaviors.

---

## **Key Findings**

### **1. Sales Trends Over Time**
- **Seasonality:** December consistently showed the highest liquor sales each year, followed by June, indicating seasonal peaks during the holidays and early summer.
- **Weekly Patterns:** Fridays emerged as the most popular day for liquor purchases starting from mid-2022, overtaking Tuesdays and Wednesdays, which previously led sales.
- **Volume Trends:** Despite the overall increase in sales dollars, there was no consistent growth in liquor volume sold across the years.

### **2. County-Level Insights**
- Dallas County consistently recorded the highest average sales volume between 2012 and 2023.
- Buchanan County, reported as having a high percentage of excessive drinkers, occasionally recorded high sales volumes. However, other counties identified in news reports did not show significant sales trends, suggesting additional factors contributing to excessive drinking.

### **3. Consumer Behavior Shifts**
- Sunday sales, previously rare, showed a slight but noticeable increase starting in 2020.
- The shift toward higher sales on Fridays highlights changing consumer behavior, likely influenced by lifestyle and work pattern changes.

---

## **Data Cleaning and Preprocessing**
- **Data Types:** Corrected data types for columns like `Date`, `Zip Code`, and `Item Number`.
- **Date Features:** Extracted `Year`, `Month`, and `Day_Name` to enable time-series analysis.
- **Handling Missing Values:** Removed columns with significant missing data and redundancy, such as `Store Location` and `County Number`.
- **Column Renaming:** Standardized column names to follow a camel case convention.

---

## **Visualization Highlights**
- **Sales Trends:** Time-series plots showing monthly and yearly sales trends.
- **Weekly Sales Patterns:** Bar plots highlighting the shift in popular sales days.
- **County-Level Sales:** Heatmaps showing sales distribution across Iowa counties.

---

## **Business Implications**
- **Seasonal Promotions:** The strong sales in December and June suggest opportunities for targeted marketing campaigns.
- **Operational Adjustments:** The rise in Friday sales calls for stores to adjust operations to handle increased traffic.
- **Sunday Sales Strategy:** The gradual increase in Sunday sales may prompt stores to consider opening or extending operating hours on Sundays.

---

## **Technologies Used**
- **Data Analysis:** Python (Pandas, NumPy)
- **Visualization:** Matplotlib, Seaborn, Tableau
- **Data Cleaning:** Pandas
- **Time Series Analysis:** DateTime manipulation and aggregation
