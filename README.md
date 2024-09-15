# Financial-Multiples-Analysis-Scraper

**Purpose:** 

In investment banking and financial institutions, financial analysts often need to perform financial multiples analysis: a process where a company's value is assessed by finding the median or average of certain financial multiples (e.g., EV/EBITDA, P/E ratio) across a list of comparable companies. Traditionally, this process requires manually searching for and gathering financial data for each company, a time-consuming task, especially when dealing with a long list of companies.

This project automates that process. By taking a list of company stock tickers as input, the code scrapes relevant financial metrics from the web and returns the necessary data, reducing the time and effort required for financial multiples analysis.

**Website selection: stockanalysis.com **

-Static Website: StockAnalysis.com is a static website, meaning the financial data for each company is contained in   easily parseable table tags (<tr>, <td>).

-Regulation Compliance: The robots.txt file of StockAnalysis.com allows scraping as long as specific disallowed bots (dotbot, BLEXBot, mj12bot) are not used. This means that as long as the scraping process adheres to these regulations, this website is a suitable data source for this project.
