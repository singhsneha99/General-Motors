# General Motors Financial Data

This code extracts financial data from a GM quarterly earnings press release and cleans it for further analysis.

## Data Extraction

- The raw HTML table is extracted from the GM investor relations page using pandas read_html. 

- Header rows are set properly and unnecessary rows dropped to get a clean DataFrame.

## Data Cleaning

- Column names are renamed for clarity.

- Dollar signs, commas, and special characters are removed from financial figures. 

- Figures are converted to numeric data types.

- Percentages are converted from string to float format.

## Key Steps

- Use pandas, requests, BeautifulSoup to scrape table data from URLs

- Clean DataFrame by setting header rows, dropping unused rows, renaming columns

- Remove special characters and convert columns to appropriate data types

- Perform operations like replace and astype to transform string values to numeric

## Result

The output is a cleaned pandas DataFrame ready for financial analysis and visualization. Key columns include revenue, net income, cash flow, EPS, and operational metrics for the quarterly period.

The code demonstrates how to effectively collect, parse, and transform web-based data for analytics. The techniques used can be applied to many different types of analyses.
