# Office-Supply-Sales-Analysis
In this project, I spearheaded the comprehensive analysis of sales data to unveil strategic insights crucial for empowering the company's decision-making process."


# Sales Analysis

## Table of contents

- [Project overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)




### Project Overview

This project involves analyzing the Office Supply dataset to provide insights into sales performance and financial metrics. The primary objectives are to calculate various financial indicators, generate comprehensive reports by segment, state, and product, and identify key trends and drivers of performance. Additionally, the analysis will focus on comparing year-on-year results, assessing product profitability, and recommending potential actions based on the findings.


### Data Sources

Office supply data set: The primary data source used for this analysis is the "Office supply data.csv".

### Tools
- Excel- Data cleaning and calculation of financial metrics
- Power BI- DAX function, Visualisation


### Data cleaning
In the initial data preparation, the following tasks were performed:
1. Data cleaning.
2. Financial calculations
- Gross Sales: Total sales amount before any deductions.
- Discount: Calculated using the discount rate applied to gross sales.
- Revenue: Gross sales minus discounts.
- Profit before Tax: Revenue minus the cost of goods sold and operating expenses.
- Profit Margin: Profit before tax divided by revenue, expressed as a percentage.
- Tax on Profit: Calculated as 5% of profit before tax.
- Profit after Tax: Profit before tax minus tax on profit
- Discount Rate: Calculated using the DAX IF function in Power BI

### Exploratory Data Analysis

 Utilising Power BI, I created tables and charts to delve into sales performance by segment, state, and product, 
 extracting valuable insights from the following reports:
 
### Reports
- Segment: Analysis of sales performance by customer segment.
- State: Evaluation of sales performance by geographical location.
- Product: Assessment of sales performance by product.
- Analysis of Products Sold in 2014: number of sales, sales proportions, and financial performance of products 
  sold between January and December 2014.
- Comparison of 2013 Q4 and 2014 Q4 Figures
- year-on-year results for fourth quarter figures.
- comparison at higher levels such as product category and state.

![image](https://github.com/Bukolagbogi/Office-Supply-Sales-Analysis/assets/152001727/f630eecc-9a02-4d74-a082-81346e5e2d64)

![image](https://github.com/Bukolagbogi/Office-Supply-Sales-Analysis/assets/152001727/67456dbb-647f-41df-aecd-06a85c677ef6)

![image](https://github.com/Bukolagbogi/Office-Supply-Sales-Analysis/assets/152001727/38ce2230-eb2b-4090-81b1-36c6a6abd722)


 ### Insights
- Growth and decline in product lines
- Identification of products significantly contributing to sales revenue and profit.
- Identification of Products for Discontinuation:

- Product subcategories with poor outcomes for potential discontinuation based on financial performance.

- Analysis of Taxation on Products: products with the highest tax burden overall, for each state and customer 
  segment

![image](https://github.com/Bukolagbogi/Office-Supply-Sales-Analysis/assets/152001727/5d267723-4547-40f9-b294-8aaeee6f3548)

### Data Analysis
- Data preparation
  I imported the dataset into Excel and Power BI, meticulously cleaned the data, removed duplicates, handled 
  missing values, and rectified any errors to ensure data integrity.

- Calculations:
  In Excel, I employed various formulas to calculate critical financial metrics such as gross sales, revenue, 
  profit, and discounts. These formulas were tailored to the specific requirements of the analysis, ensuring 
  accuracy and consistency in the calculations.

  In Power BI, I leveraged DAX (Data Analysis Expressions) functions to perform similar calculations. For 
  instance, I utilized the IF function to dynamically calculate discounts based on predefined discount bands. 
  This allowed for flexible and efficient discount calculations within the Power BI environment, enhancing the 
  overall analysis process.


### Results

The analysis results are summarized as follows:

- In Q4, the standout performers driving performance were Biros and A4 papers, significantly contributing to our 
  success during this period. Conversely, Staplers showed the weakest performance, suggesting a potential 
  consideration for discontinuation to streamline our product portfolio.
- The highest overall tax payments were notably associated with Biros.
- The highest tax paid per product across states and segments can be found below;

 ![image](https://github.com/Bukolagbogi/Office-Supply-Sales-Analysis/assets/152001727/df59a9af-4c73-42e7-878b-cffd4d12cc27)



### Recommendations 
- Product Focus: Considering the strong performance of Biros, it is recommended to further capitalize on this product's 
  success by potentially enhancing marketing efforts or exploring opportunities for product line expansion or innovation.

- New B2B Segments: exploring new B2B segments, like schools and corporate offices presents an excellent opportunity for 
  business expansion. They often require a variety of supplies ranging from stationery to larger equipment, presenting a 
  potentially lucrative market for office supply businesses.



