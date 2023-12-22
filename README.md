# Excel-Atliq-Hardware-Project

Atliq Hardware Project

Business Model of Atliq: 
            Atliq is a company that sells hardware like PC, mouse, printers and so on to different stores(customers) like croma, BESTBUY, STAPLES, flipkart and then from there, these stores will sell the hardware to the end consumer person.They have manufacturing facility where they build all these hardware and then they send it to a warehouse distribution centers. They have business in different countries, so they ship it to different location and from there the material or the hardware items will go to the individual stores.

Task : To create report on Sales Analytics and Finance Analytics for Atliq using requirement file given by Atliq business users to understand the end business outcome.

1. Sales Analytics : Following methods are involved in creating report on Sales Analytics.

- Performed ETL(Extract, Tranform and Load):imported csv files into excel, then used power query to perform some transformation like replace values,converted negative values into 
  absolute value and later transform data loaded back to excel.
- Connected Dimension and Fact tables using Data modelling in power pivot by method of star schema. 
- Created dim_date table consists of column like date, month and fiscal year of Atliq using Power Query M-Language and added dim_date table to data model later connected to Fact table.
- Used Date Analysis Expression(DAX) function such as sum,calculte,divide and so on for calculating appropriate measures, created Customer Performance Report and Market Performance vs 
  Target report using Pivot table.

Purpose of sales analytics : Evaluation of financial performance, support decision-making, and facilitate communication with stakeholders.

2. Finance Analytics : Following methods are involved in creating report on Finance Analytics.

- Added finance data to data model using power query.
- Used DAX function for calculating appropriate measures.
- Derived fiscal months and quarters in dim_date table using power pivot.
- created P & L Statement by Fiscal Year Report,P & L statement by Market report, and P & L statement by quarters report using Pivot table.

Purpose of finance analytics : Aid in benchmarking against industry peers and previous periods Foundation for budgeting and forecasting.

Role of reports:Align financial planning with strategic goals instill confidence in the organization's financial outlook.
