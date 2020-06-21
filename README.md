# Sponsorship Analysis Based on Ebay

For sellers, whether to subscribe sponsorship for their products is hard to decide. This project focuses on analysing eBay’s Promoted Listings with target of playstation 4 slim product in buy-it-now listings to deliver a feasible approach for sponsorship decisions.

The project can be divided into three process.
- Web Scraping: For the first 10 pages of 100 items/page, I scrap seller name, seller score, item price, # items sold, best offer available, title, returns allowed, shipping price, condition (e.g., used, new, like new, seller refurbished, ...).
- Save to MySQl database: Data cleaning, such as price into a "dollar-cent" format (e.g., convert $12.34 into 1234 and $12 into 1200). Connect to MySQL and save the information into "eBay_items" table.
- Use SQL to Analyse: Summary stats on each item grouped by "sponsor/non-sponsor" and "condition".

It provide an apporach to build pipeline to store the information form the web and make preparation for analysis. 
