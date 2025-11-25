# **Supermarket Sales Analysis and Dashboard**

## 1. Overview
This project involved a comprehensive analysis of 3 months of supermarket sales data to identify key business insights and drive data-driven decision-making. The analysis focused on sales trends, product performance, and customer behavior, culminating in an interactive Power BI dashboard for management use.

## 2. Project Objectives
The primary goals of this analysis were to:

* **Identify** the most profitable product lines and top-performing branches.

* **Analyze** customer purchasing patterns across different demographics (gender, customer type).

* **Determine** peak sales hours and days of the week to optimize staffing and operations.

* **Provide** actionable recommendations to drive business growth.

* **Develop** an interactive dashboard for ongoing monitoring of KPIs by management.

## 3. Tools and Technologies Used
This project utilized a combination of Python for data manipulation and analysis, SQL for potential database interaction and Power BI for visualization and dashboard creation.

* **Analysis & Manipulation:**
 
  * **Python:** The core language used for data cleaning, transformation, and exploratory data analysis (EDA).
  
  * Libraries: Pandas, Numpy, Matplotlib, Seaborn.

* **Database:**

  * **SQL:** Used for querying and initial data structuring.
 
* **Visualization & Reporting:**

  * **Power BI:** Used to develop a dynamic, interactive dashboard for presenting key findings.
 
## **4. Data Analysis Approch**
my approach involved transforming raw transactional data into actionable business intelligence through a streamlined process:
* **1. Data Preparation:**

I cleaned and validated the 3-month dataset, ensuring consistency in formats (dates, times, numerical values) and handling missing information.

* **2. Feature Engineering:**

I derived new time-based metrics (hour by day, Day of the Week, month) to facilitate granular analysis of sales patterns.


* **3. Exploratory Data Analysis (EDA):**

I used Python libraries (Pandas, seaborn) to uncover trends, analyze key performance indicators (KPIs), and compare performance across branches and product lines.


* **4. Dashboard Creation:**

I utilized Power BI to synthesize these insights into a dynamic, interactive dashboard, making the results accessible and easy to monitor.


* **5. Interpretation:**

Finally, I interpreted the visualizations to generate targeted business recommendations for optimizing sales strategy and operations.

## **5. Data Source**
The analysis is based on a single CSV file containing three months of transactional records. The dataset comprises 1,000 rows and 17 columns detailing individual sales transactions.

**Key Fields:**
* **Invoice ID:** Unique transaction identifier.
* **Branch, City:** Location information for the store.
* **Customer type:** Specifies if the customer is a ”Member” or “Normal”.
* **Gender:** Customer gender (Male/Female).
* **Product line:** The category of product sold (e.g., Electronics, Food and Beverages, Health and Beauty).
* **Unit price, Quantity, Total, Tax 5%, Cogs, Gross Income, Gross margin percentage:** Key Sales and pricing information.
* **Date, Time:** Transaction timestamps.
* **Payment:** A method used for payment (E-wallet, Cash, Credit card).
* **Rating:** Customer satisfaction rating given (1 to 10).

## **6. Analysis & Key Insights**
The data analysis transformed raw transaction records into strategic insights. I identified clear patterns in sales performance, product profitability, and customer behavior over the 3-month period.

* **Branch Performance:**
    **Branch C** was the clear leader in total revenue, significantly outpacing Branches A and B.
* **Product Success:**
    **Food and Beaverages** and **Sports and Travel** were the top grossing product lines.
* **Customer Loyalty:**
    Members contributed more to sales than normal customers.
* **Demographics:**
    Female customers contributed slightly more to the total revenue than male customers.
* **Peak Times:**
    The highest volume of transactions and maximum revenue occurred daily between **5 PM and 8 PM** (evening rush hour) and       on **Saturdays**.
* **Preferred Payment:**
    E-wallet was the most favored payment method across all branches.

## **7. Actionable Recommendations**
Based on the analysis, I propose the following actions:

* **1. Optimize Peak Hours:**
  * Ensure maximum staffing from 5 PM to 8 PM (the busiest) to maximize sales volume and customer satisfaction and handle         high traffic.
* **2. Focus on Branch C:**
  * Replicate the successful strategies implemented at the top-performing Branch C across Branches A and B.
* **3. Boost Member Conversion:**
  * Implement incentives or programs to Focus efforts on converting normal customers into loyalty members.
* **4. Prioritize Top Categories:**
  * Increase inventory and promotional activity for **Food & Beverages** and **Sports & Travel**, which were identified as       the highest-grossing product lines.
 
## **8. Dashboard**
<img width="975" height="541" alt="image" src="https://github.com/user-attachments/assets/c95f5f8f-62a6-4d50-aea4-cd0a64b88014" />

* Sales by Branch C
<img width="975" height="544" alt="image" src="https://github.com/user-attachments/assets/c54efc51-68be-4d5b-b8dc-6a02dfa0143d" />

## **9. Repository Structure**

* data/: Contains cleaned dataset file (cleaned_supermarket_sales.csv).
* notebooks/: Contains the Python notebooks with the full EDA, cleaning, and analysis process (e.g.,supermarket_sales_analysis.ipynb).
* powerbi_dashboard/: Contains the Power BI file (sales_dashboard.pbix).



