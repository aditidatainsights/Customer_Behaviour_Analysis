📊 Customer Behavior Analysis

Overview  
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.
The workflow integrates "Python (pandas)" for data cleaning and feature engineering, "PostgreSQL" for structured queries, and "Power BI" for interactive dashboards.

Tech Stack  
- Python: pandas, NumPy, matplotlib  
- SQL: PostgreSQL for business transaction analysis  
- Power BI: Interactive dashboards and visualizations  

Project Workflow  
1. Data Preparation (Python)  
   - Handled missing values in review ratings  
   - Standardized column names  
   - Created age groups and purchase frequency features  
   - Loaded cleaned dataset into PostgreSQL  
2. SQL Analysis
   - Revenue by gender and age group  
   - High-spending discount users  
   - Top-rated products  
   - Shipping type comparison  
   - Subscribers vs. non-subscribers  
   - Discount-dependent products  
   - Customer segmentation (New, Returning, Loyal)  
   - Repeat buyers vs. subscription likelihood  
3. Power BI Dashboard
   - Revenue and sales by category  
   - Subscription status breakdown  
   - Customer demographics and shipping preferences  

Key Insights  
- Male customers generated nearly "2× more revenue" than female customers  
- "Loyal customers" dominate with 3,116 out of 3,900  
- "Discount-heavy products" include hats, sneakers, and coats  
- "Young Adults" contributed the highest revenue (~62K)  
- Express shipping customers spent slightly more than standard shipping users  

Business Recommendations  
- Promote "exclusive subscriber perks"
- Launch "loyalty programs" for repeat buyers  
- Balance "discount policies" to protect margins  
- Spotlight "top-rated products" in campaigns  
- Target "high-value age groups" and "express-shipping users" 

 How to Use  
- Clone the repo  
- Run Python scripts for data cleaning and feature engineering  
- Use SQL queries in PostgreSQL for structured analysis  
- Open the Power BI dashboard for interactive insights  

“This project was inspired by YouTube tutorial @amlanmohanty and adapted for learning purposes. Original code is licensed under MIT.”
