### Install scrapy
``````
pip install scrapy
``````
### Create a Scrapy Project
#### Once scrapy is installed, you can create a new Scrapy project using the following command
``````
scrapy startproject your_project_name
``````
### Define the spider
``````
cd your_project_name
scrapy genspider spider_name example.com
``````
### Run the spider
``````
scrapy crawl spider_name
``````