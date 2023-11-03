# Crawling-journal

I used BeautifulSoup library to crawl data journals of publisher Elsevier in website sciencedirect.com, website is equipped with server couldfare and then protection layer of website is strong. So, crawling data faced with several challenges. To solve its problems, we need to add user-agent in response. it is quite easy for using b4s to crawl data but it take large interval of time, about 45 mins for total journals (4831).

If using Scrapy, running program will be faster. But, as mentioned, because of sotiphiscated preventing of website, crawling data is quite stricky. I found out solutions that we need to implement user-agent rotation by faking user-agents and/or buy proxy service to be unblocked.
