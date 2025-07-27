# Shopping Trends Analysis

This project explores shopping behavior using real data pulled from SQL Server. It includes:
- Data cleaning
- Statistical analysis (including ANOVA)
- Customer segmentation
- Visual insights with Power BI

##  Files Included
- `shopping_trends.csv` - Raw data
- `shopping_trends.ipynb` - Jupyter notebook with analysis
- `Final_sheet.xlsx` - Cleaned dataset output
- `shopping_trends.pbix` - Power BI dashboard

##  Key Insights
-Gender Spending Patterns  
While women have a higher average purchase amount per transaction, men contribute more to total revenue, likely due to higher purchase frequency or volume.  

-Seasonal Trends  
Fall is the most profitable season in terms of total revenue.  
Summer shows the lowest revenue, despite notable demand in certain categories like footwear.

-Payment Method Performance  
Credit Card users generate the highest total revenue.  
Venmo users have the highest average purchase amount per transaction.  

-Age Group Analysis  
Seniors (50–75 years) are the most profitable age segment overall.  
Youth (0–24 years) have the highest average purchase per customer but contribute the least in total revenue.  

-Product Category Demand  
Clothing is the most in-demand category for both genders and across all seasons, especially during Spring.  
Footwear sees a notable increase in demand during Spring and Summer.  
Outerwear is consistently the least in-demand category across all seasons.  

=Customer Visit Frequency & Value  
Moderate Visitors contribute the most to overall revenue, making them the most valuable customer segment.  
Frequent Visitors contribute less revenue on average, indicating lower-value or discount-driven purchases.  

-Customer Satisfaction & Spending  
Customers with "Good" and "Satisfied" ratings have higher average and total spending than others.  
The majority of customers fall within the "Good" rating category.  



##  Tools & Libraries  
- Python (Numpy, Pandas, Plotly, Seaborn, Scipy)  
- SQL Server (via PyODBC)  
- Power BI  
