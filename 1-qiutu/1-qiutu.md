**项目一：1-qiutu.py**爬取‘糗事百科’-‘糗图’中图片，保存在`qiutu`文件夹中
刚开始尝试着实战爬虫的第一段程序。

通过‘糗事百科’-‘糗图’中的前端代码可以发现：所有的图片地址都藏在
`<div class="thumb">`下面。


```python
<div class="thumb">

<a href="/article/121001741" target="_blank">
<img src="//pic.qiushibaike.com/system/pictures/12100/121001741/medium/ARQKDJMKTJE0TKVP.jpg" alt="哈哈哈" />
</a>
```



