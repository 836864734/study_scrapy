# study_scrapy
学习python scrapy爬虫框架

### 新建项目
```
scrapy startproject mySpider
```
### 爬取网页源码
```
scrapy genspider itcast "itcast.cn"
```

### 保存爬取的数据
```
scrapy genspider itcast "itcast.cn"
scrapy crawl itcast -o teachers.jsonl
scrapy crawl itcast -o teachers.csv
scrapy crawl itcast -o teachers.xml
```
