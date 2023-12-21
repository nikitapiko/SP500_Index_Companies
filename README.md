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

Preview:
![output_91_0](https://github.com/nikitapiko/SP500_Index_Companies/assets/78175001/75f6f788-3f4f-4836-8a9f-9303df5ca4ea)

![output_92_0](https://github.com/nikitapiko/SP500_Index_Companies/assets/78175001/b68b90c5-f052-4c56-bc88-509be18b6586)

![output_93_0](https://github.com/nikitapiko/SP500_Index_Companies/assets/78175001/b40c077d-c2ab-43dc-bb49-441bd4e1ee04)

![output_103_0](https://github.com/nikitapiko/SP500_Index_Companies/assets/78175001/a3efba6e-55cd-4c16-a33f-f93592bae970)
