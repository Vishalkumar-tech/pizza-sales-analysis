# pizza-sales-analysis
📁 Dataset Overview
The dataset analyzed in this project is pizza_orders.csv, which contains information about individual pizza orders, including:
order_id
pizza_id
quantity
date
time
The data was processed to understand patterns and visualize the following aspects:
Most popular pizzas
Orders by hour of day
Orders by day of the week
Weekly and daily order trends

🧹 Data Preprocessing
Missing Values Check:
Any missing values were identified and dropped accordingly:
Column Fixing & Feature Engineering:
Created new columns like month, hour, day_of_week, and week_of_year.
Converted date and time to proper datetime formats for time-based analysis.
Extracted hour from the time column to analyze hourly trends.

🔍 Exploratory Data Analysis (EDA)
⏰ Hourly Distribution of Orders
Analyzed when customers place the most orders during the day.

🍕 Top 10 Most Popular Pizzas
Identified which pizzas were ordered most frequently.

📆 Daily Order Trends
Showed how the number of orders fluctuates on a daily basis.

📅 Orders by Day of the Week
Identified which weekdays are the most popular for ordering pizza.

📈 Weekly Order Trends
Explored how orders changed on a weekly basis throughout the year.

📊 Tools and Libraries Used
Pandas - for data manipulation
NumPy - for numerical computations
Matplotlib & Seaborn - for data visualization
Scikit-learn - for additional preprocessing and modeling

📌 Key Insights
The busiest hours for pizza orders are likely around lunchtime and dinner hours.
Certain pizzas like big_meat_s were significantly more popular than others.
Fridays and weekends saw a spike in the number of orders, indicating peak pizza consumption times.
The weekly trends showed seasonal or promotional effects possibly influencing order volume.

🚀 Future Enhancements
Use a time-series forecasting model (like ARIMA or Prophet) to predict future sales.
Analyze revenue trends by combining sales with price data.
Cluster customers based on order times and pizza preferences.

🧠 Conclusion
This project showcases how basic data analysis and visualization can uncover valuable insights from sales data. By understanding when and what customers order, businesses can optimize staffing, promotions, and inventory planning.
