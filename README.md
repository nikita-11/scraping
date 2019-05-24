"scraping" 
Python Libraries used from PyPI-  BeautifulSoup, Pandas and Requests.

Next the scrape function is built to scrape the number of followers for any given url. 
Scrape fucntion uses beautifulsoup to parse the page using html.parser and extract the relevant information from the anchor tags.
    input parameters  - url and name of the GIT user. 
    url = "https://github.com/OwenMelbz"
    name = "/OwenMelbz" 
    scrape(url,name) return the number of followers i.e 49 in this case. 

Next a databse is maintained using Pandas DataFrame object to store the data for all Melbourne users and their number of followers!
We scrape the user names of all the Melbourne based users from 100 over Pages and store them in a database with the number of followers using scrape functions. 

Finally the perc_follower function takes as input a url. 
    url ="https://github.com/OwenMelbz"
    perc_follower(url) returns :
      'https://github.com/OwenMelbz is in the top 67% of Melbourne Github users based on followers'
