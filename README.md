# WeiboSpider
This is a sina weibo spider built by scrapy

这个爬虫一开始是需要登陆获得微博cookie的，然后再运行爬虫

如果你的账号是买的，微博判定不是正常账号，会出现滑动宫格验证码，本项目中获取cookie的方案就不适用了，
具体可以参考[这篇文章](https://juejin.im/post/5acf0ffcf265da23826e5e20)

如果需要构建大规模的微博抓取系统，在本项目的基础上**仅仅**需要做的就是，**购买大量微博账号，维护一个账号池**

购买微博账号的地址是[这里](http://www.xiaohao.shop/)，访问需要翻墙。

如果确实有抓取数据的需要，可以联系我，Email：xqhjay@foxmail.com

## 使用本项目
Python版本:Python3.6及以上
```bash
git clone https://github.com/SimpleBrightMan/WeiboSpider.git
# 首先获取cookie，并存入数据库中
python cookies.py
# 然后运行爬虫
python run.py
```
