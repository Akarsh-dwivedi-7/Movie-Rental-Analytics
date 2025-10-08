🎬 Movie Rental Analytics Project  
Tools Used: 🧩 SQL | 📊 Power BI | 📗 Excel  

📖 Introduction  
This project analyzes a Movie Rental Database using SQL, Excel, and Power BI.  
The goal was to understand customer behavior, film inventory, staff efficiency, and store performance, then present actionable insights through a dynamic dashboard.

⚙ Project Workflow  

🧹 1. Data Extraction & Cleaning (SQL)  
- Queried multiple tables: Customers, Films, Rentals, Payments, Staff, Stores  
- Merged related tables (customer → address → city → country)  
- Removed duplicates and handled missing values  
- Created fact and dimension tables to support a star schema

🔍 2. Exploratory Data Analysis (EDA)  
- Answered 15+ business questions on customer loyalty, film demand, seasonal trends, and staff performance  
- Exported results to Excel for visualization and trend analysis  
- Used charts and pivot visuals instead of raw tables for better storytelling  

📊 3. Dashboard Building in Power BI  

🧱 Data Model  
- Designed a Star Schema  
  - Fact Tables: Rentals, Payments  
  - Dimension Tables: Customers, Staff, Stores, Films, Dates  
- Merged lookup tables (address, city, country, category, language) into dimensions  
- Simplified relationships to improve DAX performance  

📐 Key Measures (DAX)  
- Total Revenue → SUM of payments  
- Total Rentals → COUNT of rentals  
- On-Time Return % → Ratio of rentals returned before due date  
- Revenue per Customer → AVG revenue per unique customer  
- Rentals per Copy → Inventory efficiency  

📑 Dashboard Pages  
1. Executive Overview – KPIs, Revenue Trends  
2. Customers & Segments – RFM Segmentation, Top Customers  
3. Films & Inventory – Rentals by Category, Film × Store Matrix  
4. Staff & Store Performance – Staff Efficiency, Revenue by Store  
5. Recommendations – Summary of insights with action points  

 ⚔ Challenges in Power BI  
- Many-to-many relationships (films ↔ categories, films ↔ actors)  
- Custom time intelligence using dim_date table  
- Complex ratio measures (e.g., rentals per copy, on-time %)  
- Avoiding cluttered visuals and ensuring readability  
- Balancing business storytelling with technical accuracy 


📈 EDA Key Insights  

👥 Customer Behavior  
- Repeat customers drive higher revenue  
- Younger audiences prefer Family/Animation films  
- Age group 30–40 prefers Drama and Action

🎞 Films & Inventory  
- Action and Animation are most in-demand  
- English films dominate, but regional preferences exist  
- Stock shortages for top-performing categories  

🧑‍💼 Staff & Store Performance  
- Staff efficiency correlates with customer satisfaction  
- Stores closer to customers → 2.5× higher rental frequency  
- Peak hours: Evenings & Weekends

🌍 Seasonal & Regional Trends  
- Rentals peak during summer holidays and December  
- Romance popular in Europe, Action in the US  
- Cultural events influence movie preferences  

 🏁 Conclusion & Learnings  
✅ Applied MECE framework for structured analysis  
✅ Built an end-to-end workflow → SQL → Excel → Power BI 
✅ Highlighted insights on revenue, loyalty, inventory, and operations  
✅ Strengthened skills in SQL, DAX, Power BI, and Data Storytelling 
✅ Transformed raw data into actionable business insights

👨‍💻 Author  
*Akarsh Dwivedi*  
🔗 [LinkedIn](https://www.linkedin.com/in/akarshdwivedi/)  

⭐ If you liked this project, don’t forget to star the repository!
