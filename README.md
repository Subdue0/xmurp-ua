　　喵喵喵，这里是一个修改 UA 的小模块。细致地讲，就是用在 OpenWrt 上修改发给外网 80 端口 GET 和 POST 请求的 UA 字段 为`XMURP/1.0`再加很多个空格的内核模块，用来防止学校检测到使用代理（接路由器）。具体情况，百度“厦大路由”然后看我的简书文章就好了。在 WNDR4300 OpenWrt 18.06.1（内核 4.9.120）测试似乎没问题。

　　这是我第一次在 GitHub 上搞自己的仓库，可能会有些小问题哈。要是有的话，请各路大佬指正。