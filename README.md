# Baidu_Baike_HistoryList_Link_demo
Crawl the link of history list in the entry

Reference from https://segmentfault.com/a/1190000008241040#articleHeader10.

## How to run
`python spider_main.py`

## How to change the test link
Modify the root_url in the `spider_main.py`

```
if __name__=='__main__':
    root_url = 'https://baike.baidu.com/item/%E9%83%AD%E6%96%87%E8%B4%B5/16550438'
    obj_spider = SpiderMain()
    obj_spider.craw(root_url)
```

