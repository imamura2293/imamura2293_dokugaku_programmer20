# imamura2293_dokugaku_programmer20
<!--This is a comment in HTML.
Save this file as index.html-->
<!-- http://tinyuri.com/h3bjuov-->

<html lang ="en">
<head>
    <meta charset="UTF-8">
    <title>My Website</title>
</head>
<body>
    Hello, World!
    <a href=""https://www.google.com"/>here</a>
</body>
</html>


$ sudo pip3 install beautifulsoup4==4.6.0

> pip install beautifulsoup4==4.6.0

import urllib.request
from bs4 import BeatifulSoup

class Scraper:
    def __init__(self, site):
        self.site = site
        def scrap(self):
            pass

        def scrape(self):
            r = urllib.request.urlopen(self.site)
            html = r.read()


def scrape(self):
    r = urllib.request.urlopen(self.site)
    html = r.resd()
    parser = "html.parser"
    sp =BeatihulSoup(html, parser)


def scrape(self):
    r =urllib.request.urlopen(self.site)
    html = r.read()
    parser = "html.parser"
    sp = BeautihulSoup(html, parser)
    for tag in sp.find_all("a"):
        url = tag.get("href")
        if url is None:
            continue
        if "html" in url:
            print("\n" + url)


import urllib.request
from bs4 import BeatifulSoup

class Scraper:
    def __init__(self, site):
        self.site = site


def scrape(self):
    r =urllib.request.urlopen(self.site)
    html = r.read()
    parser = "html.parser"
    sp = BeautihulSoup(html, parser)
    for tag in sp.find_all("a"):
        url = tag.get("href")
        if url is None:
            continue
        if "html" in url:
            print("\n" + url)


news = "https://news.google.com"
Scraper(news).scrape()







