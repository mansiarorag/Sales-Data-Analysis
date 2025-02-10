# Sales-Data-Analysis

![rainbow](https://github.com/user-attachments/assets/1ec3de2b-041e-474c-a8bb-e18c98974d2e)

**Table of Contents**

  •	About This Project
  
  •	What's in This Repository?
  
  •	Data Description
  
  •	Key Insights
  
  •	SQL Queries
  
  •	Tools Used
  
  •	How to Use This Project


![rainbow](https://github.com/user-attachments/assets/1ec3de2b-041e-474c-a8bb-e18c98974d2e)

**About This Project**

  This project analyzes a dataset containing sales data to identify key trends and insights, such as total sales, top-selling cities, products, and store types. SQL scripts and Python were used for analysis, and the project is hosted on GitHub for easy sharing.

![rainbow](https://github.com/user-attachments/assets/3260e1be-13b8-4620-9376-15df0e66a279)

**What's in This Repository?**

  **1. SQL Scripts:** To explore data and calculate key metrics.
  
  **2. Google Colab Notebook:** For Python-based data analysis.
  
  **3. Results and Insights:** Key findings from the data.

  ![rainbow](https://github.com/user-attachments/assets/3260e1be-13b8-4620-9376-15df0e66a279)

**Data Description**

**Dataset:** sales_data

Columns include:

  •	**TransactionAmount (numeric):** Transaction value for each sale.
  
  •	**DiscountPercent (numeric):** Discount percentage applied.
  
  •	**ProductName (text):** Name of the sold product.
  
  •	**City (text):** City where the transaction occurred.
  
  •	**PaymentMethod (text):** Payment method used (e.g., Cash, UPI).
  
  •	**StoreType (text):** Store type (e.g., Online, In-Store).
  
  •	**CustomerAge (numeric):** Age of the customer.
  
  •	**FeedbackScore (numeric):** Feedback score provided (1-5 scale).
  
  •	**Returned (text):** Whether the product was returned (Yes or No).
  
  •	**Region (text):** Geographical region (e.g., North, South).
  
  •	**DeliveryTimeDays (numeric):** Number of days for product delivery.
  
  •	**ShippingCost (numeric):** Cost incurred for shipping.

![rainbow](https://github.com/user-attachments/assets/18dfa74b-4b0b-4b60-b009-73be2ae646a3)

**What Does the Data Show? - SQL Query Results**

**1. Aggregated Insights**

  **•	Total Sales Amount:** ₹10,202.66 million
  
  **•	Average Discount Given:** 25%
  
  **•	Top 5 Best-Selling Products:**
  
      o	Notebook (90,294 sales)
      
      o	T-Shirt (90,187 sales)
      
      o	Apple (89,970 sales)
      
      o	Laptop (89,809 sales)
      
      o	Sofa (89,740 sales)
      
**2. Drill-Down Insights**

 **•	Sales by City:**
 
      o	Kolkata (₹1,027.33 million)
      
      o	Ahmedabad (₹1,023.68 million)
      
      o	Bangalore (₹1,022.38 million)

 **•	Sales by Payment Method:**

      o	Cash (₹2,556.68 million)
      
      o	Debit Card (₹2,552.37 million)
      
      o	UPI (₹2,530.18 million)

 **•	Sales by Store Type:**
 
      o	In-Store (₹5,078.88 million)
      
      o	Online (₹5,078.05 million)

**3. Customer Behavior Analysis**

  **•	Sales by Age Group:**
  
      o	50+ (₹4,316.36 million)
      
      o	36-50 (₹2,673.04 million)
      
   **•	Average Feedback Score by City:**
   
      o	Pune, Lucknow, Chennai (3.01)
      
      o	Mumbai, Kolkata, Hyderabad (3.00)

  **•	Total Returns by Product:**
  
      o	Notebook (45,061 returns)
      
      o	Apple (45,033 returns)
      
**4. Delivery & Shipping Analysis**

 **•	Average Delivery Time by Region:**
 
      o	North (4.98 days)
      
      o	South (5.07 days)
      
 **•	Average Shipping Cost by Store Type:**
 
      o	In-Store (₹438.70)
  
      o	Online (₹433.07)

![rainbow](https://github.com/user-attachments/assets/b00a5393-41e9-468d-a76c-c2c9909ddf3b)

**Tools Used**

  •	**Python:** For analyzing and summarizing data.
  
  •	**SQL:** For writing queries to explore the data.
  
  •	**Google Colab:** To run Python code.
  
  •	**GitHub:** To share the project.

