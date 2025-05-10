![SYNTAX Project Dashboard by David Osatuyi](https://github.com/user-attachments/assets/de186e5d-3d6b-4397-9709-9952859f71a4)
This report provides a structured analysis of the profit data of Syntax Supermarket and its stores for 2023. It entails the story data and all processes taken to achieve our insights. Below are the sections for the report;

● Introduction

● Story of Data

● Data Splitting and Preprocessing

● Pre-Analysis

● In-Analysis

● Post-Analysis and Insights

● Data Visualizations & Charts

● Recommendations and Observations

● Conclusion

● References & Appendices

INTRODUCTION

Objective Of The Project

This project solely wants to examine the products with the most profitable category, their sales trends, the region of sales, and the sales rep in charge of the sales output, upon analyzing the data.

Problem Being Addressed

The report wants to determine the key drivers of the most profitable category, recognize seasonal trends, and optimize sales strategies that will enhance sales and profit.

Key Datasets and Methodologies

Datasets: Sales data, region of sales, profit sales channel, transaction type, and product categories.

Methods: Data Cleaning, Pivot Tables, and Dashboard Creation

STORY OF DATA

Data Source

Internal sales database for Syntax Supermarket and stores.

Data Collection Process

The data was gathered through automated sales transaction logs.

Data Structure

Each row represents an individual sales transaction, including order details and product specifications, while each column has different independent and dependent variables, e.g., salesperson, region, payment method, etc.

Important Features and Their Significance

● Order Date: Determines sales trends over time.

● Category: Identifies the top-selling product categories.

● Revenue: Measures total sales performance.

● Quantity: Provides insight into product demand.

● Region: Provides details about performance in different regions.

Data Limitations or Biases

None was found

DATA SPLITTING AND PREPROCESSING

Data Cleaning

● Removed repeated entries.

● Checked the date formats and put them in standard form.

● Converted revenue to numeric data and formatted it to the Naira currency.

Handling Missing Values

● Used Excel functions to fill gaps.

● Deleted rows with irrelevant records.

Data Transformations

● Creation of Profit variable was performed , thus =+[@[Sales_Amount]]-([@[Unit_Cost]]-[@Discount])

Data Splitting

● The following columns were split and identified as independent variables: sales date, sales rep region, Order Date, Customer ID, Customer type, payment method, sales channel, region and sales rep, and Product category.

● The dependent variables: Sales Amount, Postal Code, Shipped Date, Unit Price, Quantity, Revenue, Shipping Fee.

Industry Context

● Supermarket and Store Sales Data

● Knowing the industry type of data gives perspective into the analysis to be made and what success means to such a company.

Stakeholders

● CEO,

● Managing Director

● Assistant General Managers

● Finance Team

● Sales Team

Value to the Industry

● Insights from this report help optimize Profit as considered Value to the company. Maximizing Sales revenue while reducing Unit Cost.

PRE-ANALYSIS

Identify Key Trends

● The North region contributes significantly to revenue.

● Some salespersons performed more than others.

● Food has significantly higher entries than other products.

Potential Correlations

● High revenue categories had consistent order frequency.

● Cities with high revenue seem to have high-performing salespeople.

Initial Insights

● Higher discounts lead to increased sales volume but reduced profits.

● The top cities were in the top region.

● The best-performing salespersons were also in the same region.

IN-ANALYSIS

Unconfirmed Insights

● Certain states had higher-order frequencies.

● Some products and categories might have large quantity orders, but the high discount given in the category influenced the profit gained.

Recommendations

● Build stronger relationships with high-value clients.

● Expand the beverage line or run targeted promotions to sustain and potentially grow its market lead.

● I recommend that David, assisted by Alice, should be made the Sales Team Lead and Assistant, respectively. To instill the values of dedication and key strategies in other sales Rep

Analysis Techniques Used in Excel

● Pivot Tables

POST-ANALYSIS AND INSIGHTS

Key Findings

● Salesperson David drives in the most revenue.

● Food stands out as the best-performing product category.

● North is the region in which we generate most of our revenue.

Comparison with Initial Findings

None was found

DATA VISUALIZATIONS & CHARTS
![image](https://github.com/user-attachments/assets/a79deaec-7ffd-4d1f-a4e6-dd11619db4cb)


Our top performing sales reps are David, followed by Bob, and Alice
![image](https://github.com/user-attachments/assets/eec3b251-9501-4105-b85b-755a857262ea)

Our top region of sales for the year is the North region, and the East region is pretty close
![image](https://github.com/user-attachments/assets/4f2c1803-f0d3-420a-b877-96eb130328ab)

Most of our products gained more profitable sales through the retail channel rather than the online channel.
RECOMMENDATIONS AND OBSERVATIONS

Actionable Insights

1. I recommend that David, assisted by Alice, should be made the Sales Team Lead and Assistant, respectively. To instill the values of dedication and key strategies in other sales Rep

2. Promo bargains may be implemented on other products to improve customer awareness about other products in regions where they performed the least

3. Advertisement to Customers to access Online Sales will also be Profitable for the year 2024

4. The Suppliers of products to Syntax are recommended for further business bargains to continually attain a low unit cost of materials purchased for resale.

5. I recommend a management meeting with the sales team to discuss the rapid drop in profit in December 2023.

6. A Customer care representative should be employed to engage for customer feedback to retain both New and Returning Customers for the year 2024

Optimizations or Business Decisions
● Implement sales techniques from top performers like David and train underperformers like Charlie

● Allocate more marketing resources to the South region to close the sales performance gap.

● Expand electronics promotions and monitor sales trends to prevent profit depletion.

● Develop tiered pricing strategies, such as discounts for online purchases.

Unexpected Outcomes
At the moment, no unexpected outcome can be stated

CONCLUSION
Key Learnings
● Specific product categories, regions, and salespersons largely influence sales revenue.

● The most used payment method generating high profit for Syntax is the Credit card.

Limitations
No limitations

Future Research
● Conduct a deeper analysis of customer retention patterns and purchasing behaviours.

● Explore additional data sources to assess profit margins and overall business sustainability.
