# Kwanza Tukule Data Analyst Assessment


This assessment is designed to evaluate your technical, analytical, and problem-solving skills. The dataset provided represents anonymized sales data. Use it to complete the tasks below and demonstrate your ability to derive actionable insights and recommendations.

Please submit your work as a Jupyter Notebook, R script, Excel workbook, or a detailed PDF report.

## Data Source
[Data](https://www.google.com/url?q=https://docs.google.com/spreadsheets/d/1E90iFRs0fbn3cldZCQo7cGZ8XmBDYpdHuqeUEC3TGXc/edit?gid%3D1416790554%23gid%3D1416790554&sa=D&source=editors&ust=1737390314103602&usg=AOvVaw2vU-aXL-7t0lUNkRjQRZeH)

## Section 1: Data Cleaning and Preparation (20 points)

1. **Data Quality Assessment:**
   
   Inspect the dataset for missing values, duplicates, or inconsistent data types. Provide a summary of issues identified and the steps taken to resolve them.
   
2. **Feature Engineering:**
   
   Create the following columns: “Month-Year” (e.g., August 2024) from the “DATE” column. (include a screenshot of this in your submission)


## Section 2: Exploratory Data Analysis (30 points)

1. **Sales Overview:**

* Calculate total Quantity and Value grouped by:
   * Anonymized Category
   * Anonymized Business
* Provide visualizations (e.g., bar charts or tables) to support your findings.

2. **Trends Over Time:**

    Analyze sales trends (Value and Quantity) by Month-Year. Create a time series plot to show seasonal patterns or changes in sales performance.
   
3. **Performance Analysis:**
   
   * Identify the top 5 most frequently purchased products (based on Quantity).
   * Identify the top 5 most valuable products (based on Value).

4. ## Section 3: Advanced Analysis (30 points)

1. **Customer Segmentation:**
   * Perform a segmentation analysis of businesses (Anonymized Business) based on their purchasing behavior:
      * Total Quantity purchased
      * Total Value contributed
      * Frequency of transactions
   * Classify businesses into 3 groups (e.g., High Value, Medium Value, Low Value) and provide recommendations for engagement with each group.
2. **Forecasting:**
   * Using the provided data, forecast the total sales (Value) for the next 3 months. Use an appropriate time-series forecasting method (e.g., ARIMA, moving average, or exponential smoothing).
3. **Anomaly Detection:**
   * Identify any unusual spikes or drops in sales performance (Quantity or Value) and explain possible reasons based on the data.
4. **Correlation Analysis:**
   * Examine relationships between Quantity and Value. Provide insights into which factors drive sales performance.

## Section 4: Strategic Insights and Recommendations (20 points)

1. **Product Strategy:** Based on your analysis, recommend one product category to prioritize for marketing campaigns. Justify your choice using the data.
   
2. **Customer Retention:** Identify businesses that have reduced their purchase frequency over time. Suggest strategies to re-engage these customers.

3. **Operational Efficiency:** Suggest improvements to inventory management or supply chain processes based on trends in product performance and seasonal demand.

## Section 5: Dashboard and Reporting

1. **Create a dashboard summarizing key insights, including:**
   
   * Total Quantity and Value by Anonymized Category.
   * Top-performing products and businesses.
   *A time-series chart of sales trends.
   * A segmentation summary of customer groups.
2. Use tools such as Power BI, Tableau, or a Python library (e.g., Plotly, Dash) to make the dashboard interactive (if possible). Provide a screenshot or link to the dashboard.
