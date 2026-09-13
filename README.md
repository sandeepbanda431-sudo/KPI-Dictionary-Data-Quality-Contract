# KPI-Dictionary-Data-Quality-Contract
This project develops a KPI Dictionary and Data Quality Contract for an e-commerce business. It defines key KPIs such as revenue, orders, customer count, return rate, cancellation rate, delivery performance, and profit margin with clear formulas, filters, owners, and refresh schedules. 
## Files
1. ecommerce_sales_sample.csv - sample source dataset
2. KPI_Dictionary.xlsx - KPI dictionary and dataset definition
3. Data_Profile.ipynb - executable Python data-quality notebook
4. Data_Quality_Contract.docx - quality rules, thresholds and escalation actions


## HOW TO RUN THE NOTEBOOK
1. Put all files in the same folder.
2. Open Data_Profile.ipynb in Jupyter Notebook or VS Code.
3. Run all cells.
4. The notebook profiles the data and executes quality checks.
5. The sample data intentionally contains a few quality issues so that checks demonstrate how failures are detected.

## PROJECT OWNER:
Head of E-commerce / Sales Manager

QUALITY THRESHOLDS:
Completeness >= 98%
Uniqueness >= 99.5%
Validity >= 99%
Consistency >= 98%
Freshness <= 24 hours
