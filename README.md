# SP500_Index_Companies
Intended Goal: To construct two distinct tables featuring data on S&amp;P 500 companies, and then merge them into a single final table. Store all tables in a newly created database. Finally perform data analysis and create data visualizations. Look at which sectors are leading in terms of average market capitalization and company count.

Database Structure:

Database Name: sp500_stock_market_index_data
Tables:
companies_spx: Data pulled from website
columns: symbol, company_name, sector, market_cap
companies_rdf: Data acquired via SPARQL query from DBpedia.
columns: symbol, company_name, revenue, net_income, assets, equity, num_of_employees
companies_merged: The final table merged with a pandas function taking in an SQL query as input.
Final Table Specifications:

Table Name: companies_merged
Columns:
ticker: The unique stock ticker symbol for each company
company_name
sector
market_cap: the market capitalization of the company
revenue
net_income
assets
equity
num_of_employees

Project Flow:
![bpmn_diagram](https://github.com/nikitapiko/SP500_Index_Companies/assets/78175001/dd952781-1c6c-4cb9-afbf-a3df7a5b538d)
