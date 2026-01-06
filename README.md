# Summary
In this Python-based E-commerce analysis project, I started by cleaning and understanding the dataset using functions like
head(), info(), and describe() to check data structure, data types, and summary statistics. The Order Date and Ship Date
columns were converted from object type to datetime format to enable accurate time-based analysis.
From the Order Date, I extracted new features such as Month, Year, and Day of Week, which helped in identifying sales and
profit trends over time. After data preparation, I performed data visualization using Python libraries to analyze sales and
profit patterns across different time periods, categories, and sub-categories.
The visual insights clearly highlighted seasonal trends, top-performing categories, and profitable sub-categories, helping in
better business decision-making related to sales planning, inventory management, and profit optimization.

# Context 
This project focuses on analyzing E-commerce sales data to understand sales performance, profit trends, and customer
purchasing behavior. The dataset includes information such as order dates, sales, profit, categories, sub-categories, and
customer segments.
The data was first cleaned and preprocessed using Pandas and NumPy, where missing values were handled, column data
types were corrected, and Order Date and Ship Date were converted into datetime format. Time-based features like month,
year, and day of the week were extracted to support trend analysis.
For data visualization, both Matplotlib/Seaborn and the Plotly library were used. Plotly was mainly used to create interactive
charts such as monthly sales trends, category-wise profit distribution, segment-wise sales analysis, and sub-category
comparisons. These interactive dashboards allow users to hover, zoom, and filter data for better understanding.
The insights from this analysis help identify top-performing months, high-profit categories, low-performing sub-categories,
and seasonal sales patterns, supporting better business decision-making

# Key Insights 
1. Sales show clear monthly trends, indicating seasonality in customer purchasing behavior.
2. Certain product categories consistently contribute the highest sales, making them key revenue drivers.
3. Some sub-categories generate low sales but high profit, while others have high sales with low profit margins.
4. Monthly profit does not always increase with monthly sales, showing the impact of discounts and costs.
5. A few sub-categories show low or negative profit, indicating pricing or cost issues.
6. Time-based analysis using extracted Month and Day of Week helped identify peak and slow period

#  Conclusion 
This analysis helped to understand how the store is performing in terms of sales and profit. By
checking monthly sales, we identified the month with the highest sales and the month with the
lowest sales. Monthly profit analysis also showed which month was the most profitable.
Sales analysis by category and sub-category showed that some products sell very well, while
others have low sales. The same pattern was seen in profit, where a few categories and sub
categories bring good profit and others give less profit or even losses.
Customer segment analysis showed that different customer groups behave differently. Some
segments give high sales, while some give better profit. The sales-to-profit ratio showed that high
sales do not always mean high profit, mainly due to discounts and costs.
Overall, this analysis helps the business focus more on high-performing products, profitable
customer segments, and the best sales months, while improving or controlling low-performing
areas.

# Recommendation
1. Focus marketing and inventory planning on high-sales and high-profit months to maximize revenue.
2. Improve pricing, promotions, or cost control for low-profit sub-categories.
3. Increase visibility and stock for high-performing categories and sub-categories.
4. Re-evaluate discount strategies during high-sales months to protect profit margins.
5. Plan special offers and campaigns during low-sales months to boost demand.
6. Use day-of-week insights to optimize staffing, promotions, and delivery planning.
