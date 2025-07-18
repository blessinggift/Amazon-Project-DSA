Amazon Product Review Analysis
📌 Project Objective
This project analyses product reviews and sales performance on Amazon. The goal is to uncover actionable insights around pricing, ratings, discount impact, and revenue drivers. These insights can help sellers improve product offerings, optimize promotions, and increase customer satisfaction.
________________________________________
📂 Dataset Overview
•	Source: Provided by Incubator Hub (scraped Amazon data)
•	Records: 1,465 rows
•	Fields: Product name, category, pricing, rating, discount, and customer engagement
•	Category Focus: Mostly Computers & Accessories
________________________________________
🛠️ Tools Used
•	Microsoft Excel
o	Data Cleaning
o	Calculated Columns
o	Pivot Tables
o	Dashboard Creation
________________________________________
🔁 Analysis Workflow
1.	Loaded and reviewed dataset
2.	Cleaned data (fixed text format, removed noise, created calculated fields)
3.	Created calculated columns
o	Price Buckets (e.g., ₹200–₹500, >₹500)
o	Discount Type (High, Medium, Low)
o	Potential Revenue = Discounted Price × Rating Count
o	Rating Score = Rating × Rating Count
4.	Exploratory Data Analysis (EDA) using PivotTables
5.	Built dashboard in Excel to visualize trends and comparisons
________________________________________

📊 Key Questions Answered
No.	Question
1	Average discount % by category?
2	How many products per category?
3	Total reviews per category?
4	Which products have the highest ratings?
5	Avg. actual vs discounted price per category?
6	Products with the highest number of reviews?
7	Products with 50%+ discounts?
8	Distribution of product ratings?
9	Total potential revenue by category?
10	Unique products per price range?
11	How does discount affect rating?
12	Products with fewer than 1,000 reviews?
13	Categories with highest discounts?
14	Top 5 products by rating × review count?
________________________________________
📈 Dashboard Visuals
The final dashboard includes:
•	Average discount % by category (bar chart)
•	Product count by category (pie chart)
•	Revenue by category (column chart)
•	Rating distribution (bar chart)
•	Price range segmentation
•	Rating vs Discount scatterplot
•	Slicers for interactive filtering by Category and Price Bucket
________________________________________
🔍 Key Insights
•	High Discount Strategy Pays Off: Products with high discounts (up to 90%) still maintain strong customer ratings (avg 4.0+).
•	Top Earners: Products like Boat Deuce USB and Ambrane 60W generate the most potential revenue due to high reviews and price balance.
•	Target Price Buckets: ₹200–₹500 and >₹500 ranges hold the best-performing products.
•	Rating Score Helps Prioritize: Weighted score = Rating × Count helps find top performers.
•	Electronics Rule: Most products are under Computers & Accessories, making it a strong niche for growth.
________________________________________
🧠 Recommendations
•	Focus on products with strong reviews + high discounts for promotions
•	Promote top-scoring products using Rating Score
•	Reduce investment in low-demand categories (e.g., Toys & Games)
•	Continue monitoring mid-to-high priced items for customer loyalty
________________________________________
⚠️ Limitations & Next Steps
•	Dataset lacks sentiment analysis (text reviews not analyzed)
•	No time-based data — future projects could explore seasonal patterns
•	Adding NLP or Power BI could extend insights
________________________________________
👨‍💻 Author
Blessing Gift
Data Analyst | Product Designer | IT Support Specialist
•	💼 Incubator Hub – DSA Graduate (3-month training)
•	📊 Tools: Microsoft Excel
________________________________________









👥

# Amazon-Project-DSA
This is the Amazon Dashboard in Excel for DSA project
