### 1. install ipython - a different shell
``````
pip install ipython
``````
### 2. edit scrapy.cfg
``````
[settings]
default = bookscraper.settings
#add this line
shell = ipython
``````
### 3. run scrapy shell
#### on terminal
``````
scrapy shell
``````
### 4. sample commands
``````
fetch('https://books.toscrape.com')
``````