🧾 📊 Food Delivery Data Analysis using SQL
🟢 Objective

To analyze food order data and extract insights related to pricing, customer behavior, and restaurant performance using SQL.

🟢 Dataset Overview
Total Orders: 6,540
Dataset includes restaurant, category, price, and rating information
🟢 Data Cleaning
Renamed columns for consistency
Converted data types (Price, Rating, Date)
Checked for duplicates (none found)
Identified repeated items as valid transactional data
🟢 Key Performance Indicators (KPIs)
Total Sales: ₹1,736,185.03
Total Orders: 6,540
Average Rating: 4.27
Total Rating Count: 183,034
Average Rating Count per Dish: 27.99
📌 Insights:

• The dataset shows strong sales volume with consistent customer demand.
• The average rating indicates high customer satisfaction.
• Customer engagement is uneven, with most dishes receiving low interaction.
• A small number of dishes dominate total ratings.

🟢 Exploratory Data Analysis (EDA)
🔹 Top 5 Most Expensive Dishes

Premium dishes are primarily party combos and gift hampers, indicating higher spending on bulk and special occasions.

🔹 Average Price by Category

Categories like “Kids Special - Pizza Party” and premium pizza offerings have significantly higher prices, reflecting bulk and premium positioning.

🔹 Most Popular Dishes

Fast-food items like pizza, burgers, and combo meals dominate customer engagement.

🔹 Total Sales by Restaurant

A few restaurants such as Olio, Baskin Robbins, and KFC contribute the highest revenue, highlighting brand-driven sales.

🔹 Total Orders by Category

The “Recommended” category leads in order volume, indicating strong influence of platform recommendations.

🔹 Ranking Analysis (Window Function)

Only a few dishes within each category rank at the top in pricing, showing focused premium offerings.

🔹 Above Average Price Dishes (CTE)

Higher-priced dishes are typically premium or specialty items, often associated with richer ingredients.

🟢 Category Contribution Analysis

Revenue distribution is highly skewed, with the “Recommended” category contributing over 22% of total sales, while most other categories individually contribute less than 5%.

🟢 Advanced SQL Used
GROUP BY
Window Functions (DENSE_RANK)
Common Table Expressions (CTE)
Subqueries
🟢 Key Business Insights

• Revenue is concentrated in a few categories, especially “Recommended.”
• Customer engagement is uneven across dishes.
• Pricing varies significantly across categories and restaurants.
• Opportunity exists to improve visibility of low-performing dishes.

🟢 Data Limitation

Dataset contains data from a single city (Bengaluru), so geographic analysis was not included.

🟢 Conclusion

This analysis highlights key patterns in sales, pricing, and customer engagement, helping identify opportunities for business optimization.

🟢 Tools Used
MySQL
SQL
