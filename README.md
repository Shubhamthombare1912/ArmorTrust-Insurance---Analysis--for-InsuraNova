# ArmorTrust-Insurance--Analysis--for-InsuraNova
The project aims to analyze and deliver data-driven insights for InsuraNova, a fictional company offering coverage to both individuals and businesses

## About the Company
InsuraNova is a trusted insurance provider in India offering comprehensive and reliable plans. The company is focused on customer satisfaction and helping policyholders feel secure through tailored coverage across all age groups and cities.<br />

## Business Objective
- The company wanted to analyze:<br />
- Total revenue and customer growth trends<br />
- Daily KPIs for revenue and customer acquisition<br />
- City-wise and age-wise segmentation<br />
- Sales performance by channel<br />
- Age group behavior with policy preferences and settlement expectations<br />
- The goal was to identify key growth areas, optimize product offerings, and enhance sales channel effectiveness.<br />

## Data Sources
- The project uses 5 main datasets, structured in a star schema:<br />
- dim_customer.csv → Customer details (city, DOB)<br />
- dim_date.csv → Date hierarchy with months, weekdays, and week numbers<br />
- dim_policies.csv → Policy metadata (base cover, base premium)<br />
- fact_premiums.csv → Premium payments, sales mode<br />
- fact_settlements.csv → Settlement percentages by age<br />

## Tools & Technologies Used
- Power BI Desktop<br />
- DAX & Power Query Editor<br />
- Excel/CSV for Data Source<br />
  

