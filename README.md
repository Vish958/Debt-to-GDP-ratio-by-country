# Debt-to-GDP-ratio-by-country
Job is to scrape the national debt to GDP for each country listed in this website
Here is the website link i have scrapped 'http://worldpopulationreview.com/countries/countries-by-national-debt/'.

The population is not required to be scraped, however if you want to scrape it that's fine.

Now since this will be your first exercise, I'm gonna list below the steps you need to follow:

# First thing first please scaffold a new project called 'national_debt' and then generate a spider within that same project called "gdp_debt"

# The website does use the "http" protocol by default so there is no need to modify that in the 'start_urls' since by default Scrapy will use "http"

# Next inside the parse method make sure to iterate(loop) through all rows and yield two keys 'country_name' and 'gdp_debt'

# Finally make sure to execute the spider
