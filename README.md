# AppstoreSpider
using python2.7
练习使用scrapy 框架进行数据抓取。


## 环境准备
> pip install -r requirements.pip

由于使用到 splash 进行动态解析，需要docker容器安装 splash.

> docker pull scrapinghub/splash  
docker run -p 8050 scrapinghub/splash

我们的目标网页会交给 splash 进行动态处理。然后抓取动态生成后的数据。

## 启动爬虫
> cd AppstoreSpider  
scrapy crawl huawei

下载的数据存放为 appstore.dat
