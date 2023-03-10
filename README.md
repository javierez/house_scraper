# house_scraper
This repo is aimed to scrape FC, is the largest real estate portal specializing in the sale and rental of second-hand and new-build homes in Spain.

The main functions that this scraper should have when fully developed are:
- Gathering on-sale homes automatically [ready] - auto_scraper_v5
- Gathering rental homes automatically [almost ready] - scraper_forrent_flats
- Forecasting on-sale homes' prices based on its characteristics [ready] - for_sale_analysis
- Forecasting rental homes' prices based on its characteristics [ready] - for_rent_analysis
- Calculating the profitability of the investment for the published price based on forecasted rent [to be developed]
- Calculating the price of the investment given the desired profitability [to be developed]
- Ads removed from the webpage (sold or rented homes?) [...]
- Price reductions [...]

🔳🔳🔳🔳🔳🔳🔳🔳⬜️⬜️ 80% (?)


## Conclusions
Once I had a significantly big data sample (1200 flats scraped - 4 different neighborhoods), I tried to forecast the price based on all the attributes that I could retrieve from the webpage (floor, area, elevator, rooms, bathrooms, etc). **Price published do not always represent the sale price.** Therefore, forecasts were not as accurate as expected because people can advertise any house at any price. Sale prices represent more faithfully the value of the house advertised.

Unaccurate prices limit the tool's main functionalities (profitability or price given the desired profitability).
Considering the existing usability limitations, I will not continue developing the tool.

It was a great experience learning how to scrape, avoiding scraping traps and some metrics related to Real Estate investments.
Thanks for reading!

