``````
class DCspider(scrapy.Spider):
    name = "dcspider"

    def start_requests:
        urls = ['https://www.datacamp.com/courses/all']
        for url in urls:
            yield scrapy.Request(url = url,callback = self.parse)

    def parse(self,response):
        links = response.css('div.course-block>a::attr(href)').extract()
        for link in links:
            yield response.follow(url = link, callback = parse2)

    def parse2(self,response):
        #parse the course site here!
``````