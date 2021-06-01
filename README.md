# Sneaker Data Scraping

![picture](SneakerPhotos/boxes.jpeg)

# StockX Portion:

The first part of this project is focused on scraping data from StockX. We focused on the 5 sections that were accessible from the navigation bar (Adidas, Air Jordan, Nike, Other Brands, and Luxury Brands). We collected the url keys for all the shoes available in each category, which we were then able to search based on the keys to gather more information about the individual shoes. We then were able to find the sku for each shoe which is essentially an ID number to identify the shoe. This sku ID would then allow us to scrape the interactive plot at the bottom of the shoe's page that would give us information on the past resale prices of that specific shoe.

# Reddit Portion:

The second part of this project is focused on using PRAM to scrape Reddit. With the information we collected from the StockX portion we were able to create a list of all of the names of the sneakers. The issue was that for certain shoes there were many colorways for the same model name, so we reduced the list to only include unique shoe model names. After that we had 630 unique model names to work with which is when we decided to reduce it even more to a random sample of 30 shoes to focus on. We specified in our query that we wanted to search only on the subreddit r/Sneakers and then used the list of 30 shoe model names as keywords for grabbing posts. With that we extracted the texts, id number, and date/time of each post. Using the post id numbers we were then able to go one step further and grab the texts from the comments section, which is the data that we actually wanted to get.

# Time Series Analysis on Past Resale Prices:

(Will be updated soon)

# Text Analysis on Reddit Comments:

(Will be updated soon)
