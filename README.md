# Debt-to-GDP-ratio-by-country
Job is to scrape the national debt to GDP for each country listed in this website
Here is the website link i have scrapped 'http://worldpopulationreview.com/countries/countries-by-national-debt/'.

The population is not required to be scraped, however if you want to scrape it that's fine.

Now since this will be your first exercise, I'm gonna list below the steps you need to follow:

# First thing first please scaffold a new project called 'national_debt' and then generate a spider within that same project called "gdp_debt"

# The website does use the "http" protocol by default so there is no need to modify that in the 'start_urls' since by default Scrapy will use "http"

# Next inside the parse method make sure to iterate(loop) through all rows and yield two keys 'country_name' and 'gdp_debt'

# Finally make sure to execute the spider

I am sharing with you a step by step guide how to scrap the website.

First create virtual Environment
Go to Anaconda Navigator and then environment then create new environment.
after creating environment install 
## ipython package
## then scrapy shell
  
Now creating new Project

## mkdir projects
## cd projects
## scrapy startprojects national_debt
## now copy the website link that are mentioned above

## cd national_debt
## scrapy genspider national_debt website link
(:: remove end in slash & remove http://)
(:: All above command can be post in your virtual environment terminal)

Now go the gdp_debt.py file to write the command in Virtual studio code to execute the command 

Now i am going to tell you how to create a dataseet to get the data in cvs, json, and xml file.

In Virtual Studio go the view panel then select terminal

# conda activate name of your environment workspace
# scrapy crawl national_debt -o gdp_debt_dataset.json

Get the dataset in csv 

# conda activate name of your environment workspace
# scrapy crawl national_debt -o gdp_debt_dataset.csv

Get the dataset in xml

# conda activate name of your environment workspace 
# scrapy crawl national_debt -o gdp_debt_dataset.xml


Now Do above all task if any problem occurs let me know i will help you. Happy Scraping!!!!
