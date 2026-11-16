**E-commerce Sales \& Business Intelligence**



**Project Overview**



This project explores an e-commerce sales dataset using Power BI and Python. The aim was to understand sales performance, examine product category trends, evaluate profitability and identify useful business insights from the available data.



I completed this project as a practical business intelligence exercise, combining data preparation, interactive dashboard development and Python-based visual analysis.



**Business Problem**



An e-commerce business needs to understand which product categories generate the most revenue, how profitable its sales are and how performance varies across different months and geographical regions.



This project explores these questions through data analysis and visualisation.



Hypothetical stakeholder: Sosandar plc, a UK online fashion retailer. Sosandar is used as an example stakeholder for this academic portfolio project. The dataset is publicly available and was not supplied by the company.



**Dataset**



* Source: E-commerce Dataset – Kaggle



* Original records: 15,300



* Original columns: 18



* Working dataset columns: 14



Four potentially identifying fields were removed from the working copy before analysis:



* CustomerId



* CustomerName



* CustomerEmail



* CustomerIp



The analysis uses the remaining product, sales, time and geographical fields.



**Tools and Technologies**



* Microsoft Excel: Initial dataset inspection and preparation.



* Power Query: Data cleaning, column management and calculated columns.



* Power BI: Interactive dashboard and business performance analysis.



* Python: Additional data analysis and visualisation.



* Google Colab: Python notebook environment.



* Pandas and NumPy: Data handling and numerical calculations.



* Matplotlib and Seaborn: Data visualisation.



* GitHub: Project version control and portfolio presentation.



**Data Preparation and Calculations**



The working dataset was checked for missing values and its column data types were reviewed.



The following calculated measures were used:



* Total Cost = CostOfGood × QuantitySold



* Gross Profit = salePrice − Total Cost



* Gross Profit Margin = (Gross Profit ÷ salePrice) × 100



* Discount Amount = (ProductPrice × QuantitySold) − salePrice



The calculations assume that CostOfGood represents the cost per unit and salePrice represents total revenue after discount. These interpretations were inferred from sample records.



The month names were also converted into month numbers to ensure that monthly visualisations followed calendar order.



**Key Performance Indicators**



The analysis produced the following overall results:



KPI                                     Result



Total Revenue                        39,830,223.00



Total Cost                           22,050,381.55



Total Gross Profit                   17,779,841.45



Total Quantity Sold                      83,880



Overall Gross Profit Margin                  44.64%



Total Discount Amount                 2,326,743.00



These figures are reported in the dataset's original monetary units. The dataset does not clearly establish a currency.



**Power BI Dashboard**



The interactive dashboard includes:



* Total Revenue



* Total Cost



* Total Gross Profit



* Total Quantity Sold



* Overall Gross Profit Margin



* Revenue by Product Category



* Revenue by Country



* Monthly Revenue Trend



* Gross Profit by Product Category



* Quantity Sold by Product Category



* Revenue by Continent



* Revenue vs Gross Profit by Product Category



Interactive slicers allow the dashboard to be filtered by:



* Product Category



* Order Month



* Order Year


**Python Analysis**



Python was used to create six additional visualisations:



1. Revenue by Product Category



2\. Monthly Revenue Trend



3\. Revenue vs Gross Profit



4\. Gross Profit Margin by Category



5\. Revenue by Continent



6\. Correlation Heatmap



The notebook and chart images are included in this repository.



**Key Findings**



* Movies generated the highest revenue among the product categories.



* December recorded the highest monthly revenue, while May recorded the lowest.



* Africa recorded the highest revenue at continent level.



* Movies also recorded the highest gross profit in the Power BI analysis.



* Industrial recorded the highest quantity sold, although it ranked fifth in gross profit.



These findings show why revenue, quantity sold and profitability should be considered together when evaluating product performance.



**Business Recommendations**



Based on the analysis, the hypothetical stakeholder could:



* Investigate the factors contributing to the strong revenue performance of the Movies category.



* Review the relationship between sales volume, product costs and profitability.



* Examine monthly sales patterns when planning promotions and inventory.



* Investigate geographical performance and validate unusual country-level results before making market expansion decisions.



* Review discount strategies to understand their impact on gross profit margins.



**Project Structure**



01\_Ecommerce\_Business\_Intelligence/

│

├── README.md

│

├── data/

│

├── powerbi/

│   └── Ecommerce\_Sales\_Business\_Intelligence.pbix

│

├── notebooks/

│   └── Ecommerce\_Data\_Analysis.ipynb

│

├── screenshots/

│   ├── ecommerce\_dashboard.png

│   ├── ecommerce\_dashboard\_filtered.png

│   ├── revenue\_by\_product\_category.png

│   ├── monthly\_revenue\_trend.png

│   ├── revenue\_vs\_gross\_profit.png

│   ├── gross\_profit\_margin\_by\_category.png

│   ├── revenue\_by\_continent.png

│   └── correlation\_heatmap.png

│

├── documentation/

│   └── Ecommerce\_Sales\_Analysis\_Report.docx

│

└── sql/



**Limitations**



* The dataset contains records for 2016 and 2020 only, so it does not provide continuous annual coverage.



* The dataset does not clearly specify its currency.



* There is no unique order identifier, so individual order counts cannot be reliably established.



* The stakeholder is hypothetical; the analysis is not based on confidential company data.



* The cost and sale price interpretations are assumptions based on sample calculations.



* Geographical results, particularly for smaller territories, should be validated before making business decisions.



* Correlation does not demonstrate causation.



**Conclusion**



This project gave me practical experience in preparing an e-commerce dataset, calculating business performance measures, developing an interactive Power BI dashboard and using Python to explore additional patterns.



It also helped me understand how data analysis can support business decisions by presenting numerical results in a clear and useful way.



**References**



Onigbenga (n.d.). E-commerce Dataset. Kaggle. Dataset link



Microsoft (n.d.). Power BI Documentation. Documentation

