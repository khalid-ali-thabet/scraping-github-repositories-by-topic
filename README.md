# scraping-github-repositories-by-topic
## in this jupyter notebook I'm using the requests and BeautifulSoup libraries to download and parse github topics section page 
## and get (title, description, url)  of the top 30 topic and save these data in a csv file 
## then for each topic i get the (username, title, url, number of stars) of top 30 repositories and save these data in a csv file 
## then save these 30 csv files in a zip file named "topics"
## so, there is a 30 csv file for 30 topic, each one has data about top 30 repositories in that topic
