# Exploratory Analysis of Sales Patterns and Customer Behavior: Preliminary Insights from a Comprehensive Dataset.



## Table of Content

- [Introduction](#introduction)
- [Observations](#observations)
- [Visualisation](#visualisation)
- [Conclusion](#conclusion)
- [Recommendations for further analysis](#recommendations-for-further-analysis)












## INTRODUCTION

This report presents an initial analysis of a sales dataset aimed at understanding sales trends, product performance, and customer behavior. The dataset contains 2824 rows, 25 columns and a comprehensive information about sales transactions, including order details, customer demographics, and product lines. The purpose of this review is to gain initial insights from the dataset and to identify potential areas for further detailed analysis.





## OBSERVATIONS


### 1. Dataset Overview:

The dataset comprises of 25 columns, including attributes such as order number, quantity ordered, price each, order date, sales, status, product line, year_id, month_id, qtr_id, MSRP, product code, address 1, address 2, postal code, contact last name, contact first name, deal size, territory, order line number, and customer details like customer name, city, state, country, phone number.

· The numerical columns are as follows; quantity ordered, price each, sales, MSRP and categorical columns are product line, status, deal size.


### 2. Summary statistics:
 
Sales: The total sales amount ranges from 482.13 to 14,082.80, with an average of approximately 3,553.89 with a standard deviation of 1,841.87. The sales trend over time points that the month of November has the highest sales amongst other months with over $2 million.

Temporal Patterns:

Sales seems to have a temporal trend, potentially peaking in the 4th quarter of the year, with November recording the highest sales at over $2 million.

· Quantity Ordered: ranges from 6 to 97 units per order. The average quantity ordered is 35.09 units.

· Price Each: The unit price ranges from 26.88 to 100.00. The average price per unit is 83.66.

· Date Information: Orders are recorded from 2003 to 2005 (YEAR_ID). Quarterly and monthly distribution of orders is represented by QTR_ID and MONTH_ID.

· MSRP (Manufacturer’s Suggested Retail Price) ranges from 33 to 214, with an average of 100.72.

· Product Line and Product Code provides categorical data about the products.

· Customer Information: This includes details like customer name, phone, city, state, country, territory and contact names.

· Deal Size: This column categorizes details as Small, Medium or Large.



### 3. Initial Insights

Observation 1: Sales Distribution

· The sales values vary significantly across different countries, with the maximum sales of $3.6 million from USA and a minimum of $ 57,756.43 from Ireland.

· The year 2004 records the highest sales volume with over $4.7million from the year 2003 to 2005.

Observation 2: Temporal Patterns

· Sales seems to have a temporal trend, potentially peaking in the 4th quarter of the year, with November recording the highest sales at over $2 million.

Observation 3: Customer Distribution

· Customers are spread across various territories, states, and countries.

· A significant amount of the sales volume comes from the USA, with a record of over $3.6 million in sales.

Observation 4: Product Line Popularity

· Among the 7 Product lines, Classic Cars account for 39% of the sales volume, making them the highest sales volumes product line.

· MSRP (Manufacturer’s Suggested Retail Price) varies across different product lines, indicating a diverse product range.

Observation 5: Missing Values

Upon reviewing the dataset, the following missing values were identified:

· Address line 2 has a total 2,521 missing values.

· State has a total of 1,486 missing values.

· Postal code has a total of 76 missing values.


Below are the implications of missing values:

Data Completeness: Missing values in Address Line 2 and State columns reduce the completeness and accuracy of address details and geographic analysis.
Data Quality: Absence of postal codes can diminish the precision of location-based analyses and logistics planning.
Observation 6: Diverse Variations

Phone Number Column:

Variety of Formats: Phone numbers include different symbols such as hyphens, dots, brackets, and plus signs.
Inconsistent Structure: Entries lack a standardized format, making it difficult to process and compare phone numbers accurately.
State Column:

Mixed Representation: Some states are abbreviated (e.g., CA for California), while others are written in full (e.g., Victoria).
Lack of Uniformity: Inconsistent entries hinder geographical analysis and reporting based on state data.

Address Line 1 Column:

Format Variability: Street addresses exhibit diverse patterns, with street numbers and names not consistently formatted.
Data Integrity Concerns: Non-uniform address entries complicate location-based analyses and logistics.



## VISUALISATION

### PIE CHART: SALES BY PRODUCT LINE



![pie](https://github.com/user-attachments/assets/67be5336-8587-43b3-accb-53c856c21ef5)

The pie chart visually represents the distribution of total sales across different production lines, with Classic cars emerging as the top-selling product line. This means that Classic cars contributed the largest share of total sales compared to other product lines featured in the chart.



### COLUMN CHART: QUARTERLY SALES


![image](https://github.com/user-attachments/assets/af63f744-4f82-4926-a1e8-211ceea7fe5e)

This chart illustrates that sales peaked during the 4th quarter of the year, encompassing the months of October, November, and December. Year-end factors, seasonal demand are some of the several strategic and economic implications.



### MONTHLY SALES


![image](https://github.com/user-attachments/assets/27412ae7-3c5b-45c1-9c7c-339a1d2468e7)



The chart clearly illustrates that November, specifically the 11th month, stands out with the highest recorded sales exceeding $2 million. This peak in November indicates that it was the most lucrative month in terms of sales within the analyzed period. Several factors could contribute to this peak, such as seasonal trends, special promotions or discounts during the holiday season, increased consumer spending around festive periods like Thanksgiving or Black Friday, or strategic marketing campaigns. Businesses often capitalize on such peak periods to maximize sales, making November a critical month for revenue generation based on the data presented in the chart.



### YEARLY SALES


![bar](https://github.com/user-attachments/assets/134cc53d-1bf7-444e-a568-91ab47ebd129)


The chart presented indicates that sales volumes are plotted against years, showcasing a peak in the year 2004 where sales reached an impressive figure of over $4.7 million. This peak signifies that 2004 marked a particularly prosperous period in terms of sales performance, likely representing robust market conditions, increased consumer demand, successful product launches, or other favorable economic factors during that specific year.



### SALES BY COUNTRIES


![image](https://github.com/user-attachments/assets/7fb2cf1e-518c-40ef-bcf7-6e2bb4df1428)


A column chart showing the sales distribution by countries, highlighting a significant amount of the sales volume from the USA, with a record of over $3.6 million in sales.

It suggests that the USA plays a pivotal role in the sales landscape, likely indicating a strong market presence or consumer demand within the country compared to other nations included in the dataset.



### SALES BY CUSTOMERS


![image](https://github.com/user-attachments/assets/08cdff6a-a3db-4c22-b37d-71ee8b582a22)



The graphical illustration highlights the top 10 customers based on total sales or revenue generated. Among these top 10 customers, Euro Shopping Channel stands out as the highest-ranking entity, having contributed a significant $912,294.11. This suggests that Euro Shopping Channel has made the largest financial impact among all the listed customers within the dataset or analysis period.



## CONCLUSION

The initial analysis of the sales dataset reveals several key insights:

· The dataset includes a mix of categorical and numerical variables, with some strong correlations observed between key variables like quantity ordered and sales.

· Sales data shows distinct trends over time and varies significantly across different production lines such as “Classic Cars” and “Motorcycles,” demonstrate strong sales performance, warranting further investigation into factors contributing to their success.

· Outliers in the sales data warrant further investigation to understand their causes and potential impact on overall sales performances.



## RECOMMENDATIONS FOR FURTHER ANALYSIS

Based on the initial observations, potential areas for further analysis include:

· Seasonal Analysis: Conduct detailed seasonal decomposition to understand peak sales periods and optimize inventory management and marketing strategies accordingly.

· Product Line Analysis: Explore factors influencing the success of top-performing product lines and identify opportunities for product diversification or enhancement.

· Customer Segmentation: Perform deeper segmentation analysis to uncover distinct customer profiles and preferences, enabling personalized marketing approaches and enhanced customer engagement.














