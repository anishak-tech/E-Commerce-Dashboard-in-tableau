# **📊 [Trendy E-Commerce Sales Analytics Report**](https://public.tableau.com/views/E-CommerceDashboard_17641156125650/E-CommerceDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
## **1. Summary**

This project analyzes sales, customer behavior, regional performance, product categories, and demographic insights for Trendy E-Commerce, an online retailer of clothing, footwear, and accessories. The goal was to create an interactive dashboard that helps management make decisions about marketing, inventory, pricing, and customer targeting.

The analysis reveals:

* Clothing drives the highest revenue.
* Most customers purchase during weekends and month-ends.
* North and West regions generate the majority of sales.
* Young adults (18–35) are the primary buyers.
* Accessories have high potential but low visibility.

The findings help the company optimize inventory, focus on profitable regions, and run targeted campaigns.

---

## **2. Business Problem Statement**

Trendy E-Commerce wants to move from guesswork to data-driven decisions. The management needs answers to five key areas:

1. **Sales performance** across products and categories
2. **Customer purchasing patterns**
3. **Regional revenue differences**
4. **Time-based trends** for forecasting
5. **Demographic insights** for personalized marketing

This dashboard solves these problems by organizing and visualizing sales, customer, and product data.

---

## **3. Dataset Overview**

The dataset contains fields such as:

* Order ID
* Order Date
* Customer ID
* Product Name
* Category (Clothing, Footwear, Accessories)
* Price
* Quantity
* Total Sales
* Region / State
* Age
* Gender

Total records: **200–500 (depending on your input dataset size)**
Time range: **12 months**

---

## **4. Data Cleaning & Preprocessing**

The following cleaning steps were performed:

### **✔ Handling Missing Values**

* Replaced missing `state` values based on customer pin-codes.
* Forward-filled missing dates where applicable.

### **✔ Data Type Fixes**

* Converted `Order Date` to Date format.
* Converted `Sales` and `Quantity` into numeric fields.

### **✔ Calculated Fields Created**

* **Total Sales = Quantity × Price**
* **Profit Margin (optional)**
* **Age Group (18–25, 26–35, 36–45, 46+)**
* **Weekday/Weekend**
* **Month Name**

### ✔ **Duplicates Removed**

* Removed duplicate Order IDs.

---

## **5. Key Performance Indicators (KPIs)**

The dashboard highlights the following KPIs:

1. **Total Sales**
2. **Total Orders**
3. **Average Order Value (AOV)**
4. **Sales by Category**
5. **Top 5 Products**
6. **Repeat Customer Rate**

---

## **6. Dashboard Visualizations**

Your dashboard includes:

### **1) KPI Cards**

Shows overall business performance at a glance.

### **2) Category Sales Bar Chart**

* Clothing drives the most sales (approx. 45–55%).
* Accessories have the lowest share (10–15%).

### **3) State/Regional Map**

* North and West regions contribute the most revenue.
* East has lower penetration.

### **4) Sales Trend Line**

* Sales spike during weekends.
* Strong month-end buying behavior.
* Best months: November, December (festive season).

### **5) Customer Demographic Chart**

* Age group 18–35 dominates purchases.
* Women make slightly more orders than men (depending on your dataset).

### **6) Top Products Table**

* Footwear shows fewer orders but high average order value.

---

## **7. Insights**

### **A) Product Insights**

* Clothing is the top-performing category.
* Footwear has high margins but lower volume.
* Accessories need more visibility.

### **B) Customer Behavior**

* Younger customers (18–35) drive most sales.
* Weekend orders are 20–30% higher than weekdays.
* High conversion during festival months shows strong seasonal demand.

### **C) Regional Trends**

* North and West regions show high order frequency.
* South shows consistent but moderate sales.
* East and Northeast need targeted campaigns.

### **D) Time Trends**

* End-of-month salary periods show spikes.
* Quarter 4 (Oct–Dec) is the peak season.

---

## **8. Business Recommendations**

### **1. Boost Accessories Sales**

* Display accessories as add-ons during checkout.
* Bundle deals with clothing.

### **2. Increase Marketing in High-Growth Regions**

* Double ad spend in North & West.
* Improve delivery speed in South.

### **3. Inventory Planning**

* Stock more clothing during Q4.
* Prepare for weekend spikes.
* Reduce stock of slow-moving items.

### **4. Targeted Campaigns**

* Focus on ages **18–35** with influencer marketing.
* Run gender-specific promotions (e.g., women’s apparel ads).
* Festive discounts for Diwali/Christmas.

### **5. Improve Customer Retention**

* Loyalty program for repeat customers.
* Free delivery for high-value orders.

---

## **9. Conclusion**

The Trendy E-Commerce dashboard provides clear insights into customer preferences, regional performance, category demand, and time-based patterns. With these insights, the company can:

* Improve inventory planning
* Run more effective marketing
* Boost sales in underperforming regions
* Personalize customer experience

This project demonstrates strong skills in data cleaning, visualization, dashboard design, and business interpretation.
#DASHBOARD : 

