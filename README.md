# Excel-Atliq-Hardware-Project

Atliq Hardware Project

Business Model of Atliq: Atliq is a company that sells Hardware like PC, mouse, printers and so on to different stores(customers) like croma, BESTBUY, STAPLES, flipkart and then from there , these stores will sell the hardware to the end consumer person.They have manufacturing facility where they build all these hardware and then they send it to a warehouse distribution centers. They have business in different countries, so they ship it to different location and from there the material or the hardware items will go to the individual stores.

Task : To create report on Sales Analytics and Finance Analytics for Atliq using requirement file given by Atliq business users to understand the end business outcome.


1. Sales Analytics : Following methods are involved in creating report on Sales Analytics.

- Performed ETL(Extract, Tranform and Load):imported csv files into excel called Extract, then used power query to perform    some transformation called Transform like replace values,converted negative values into absolute value and later       transform data loaded back to excel and the data added to data model called Load.
- Connected Dimension and Fact tables using Data modelling in power pivot by method of star schema. 
- Created dim_date table consists of column like date, month and fiscal year of Atliq using Power Query M-Language and   added dim_date table to data model later connected to Fact table.
- Used Date Analysis Expression(DAX) function such as sum,calculte,divide and so on for calculating appropriate measures, created   Customer Performance Report and market performance vs target report using Pivot table.

Purpose of sales analytics : Evaluation of financial performance, support decision-making, and facilitate communication with stakeholders.

2. Finance Analytics : Following methods are involved in creating report on Finance Analytics.

- Added finance data to data model using power query
- Used DAX function for calculating appropriate measures, created P & L by Fiscal Year Report using Pivot table.
- Derived Fiscal months and quarters in dim_date table using power pivot, created P & L statement by Market report and GM%   by quarters.

Purpose of finance analytics : Aid in benchmarking against industry peers and previous periods Foundation for budgeting and forecasting.

Role of reports:Align financial planning with strategic goals instill confidence in the organization's financial outlook.


