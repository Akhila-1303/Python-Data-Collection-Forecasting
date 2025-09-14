# Python-Data-Collection-Forecasting
Dataset Overview

Rows: 1,200

Columns: 10

Date range: Contains a Date column (string format)

Key Metrics:

Base_Price and Discounted_Price

Units_Sold, Revenue

Rating and Discount (%)

Cloumn Details

| Column Name        | Description                              |
| ------------------ | ---------------------------------------- |
| `Date`             | Date of sale                             |
| `Product_ID`       | Unique product ID                        |
| `Product_Name`     | Name of the product                      |
| `Category`         | Product category                         |
| `Base_Price`       | Original product price                   |
| `Discounted_Price` | Price after discount                     |
| `Units_Sold`       | Quantity sold                            |
| `Revenue`          | Revenue generated (`Units_Sold * Price`) |
| `Discount (%)`     | Discount percentage                      |
| `Rating`           | Average customer rating                  |

📈 Forecasting Insights Summary (Using Prophet)
🔹 1. Overall Trend
The Prophet model shows a gradual upward trend in revenue over time.
This indicates steady business growth, likely due to consistent product performance or recurring customer engagement.
🔹 2. Weekly Seasonality
Weekly trend components reveal higher sales during weekends, particularly on Saturdays and Sundays.
Lower revenue mid-week, especially on Tuesdays and Wednesdays, suggests potential to boost engagement on these days through promotions.
🔹 3. Forecast Output
The forecast projects daily revenue for the next 30 days.
The trend line remains mostly stable to slightly increasing, with confidence intervals indicating potential revenue fluctuations.
🔹 4. Actionable Takeaways
Marketing Strategy: Consider targeting low-performing weekdays with special offers or campaigns.
Inventory Planning: Use trend forecasts to manage stock levels for high-traffic days.
Financial Planning: Helps leadership set realistic short-term revenue goals based on data-driven insights.
🔹 5. Limitations
Forecast is purely based on historical data; it does not account for external factors like upcoming holidays, promotions, or market changes.
Accuracy improves with more historical data points and additional regressors (e.g., holidays, events).
✅ The Prophet forecast offers valuable insight into expected short-term performance, helping guide operational and strategic decisions with data-backed confidence.
