# newspaper_scrapperr 
here i've bulid a news paper scraper by scrapy.for building a new scrapy project you need type
'scrapy startproject project_name'.In my case it is news_scrapy. this will craete a directory with this name. where you will find your spider.
Now you can build your own spider here. In my case I've the spder as it can crawl the pages by following the date of the news. Remenber this part of my code can vary according to the website complexity.

for making a spider in colab you may follow the run.ipynb .
then copy  and paste the second part of newspaper_scraping.ipynb file into your spider.
after doing all of these run your spider by typing -> scrapy crawl spider_name o filename.json.
this will crawl the web pages and save the data in jason format inside your scrapy project
