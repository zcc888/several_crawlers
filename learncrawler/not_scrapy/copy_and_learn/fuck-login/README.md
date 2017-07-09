# fuck-login

## 模拟登录一些常见的网站

主要基于以下的 Python 的第三 library 


1. [requests](http://www.python-requests.org) 处理登录
2. [pillow](https://github.com/python-pillow/Pillow) 处理验证码
3. [rsa](https://stuvel.eu/rsa) 处理加密问题

## Done

1. [知乎](http://zhihu.com)
2. [126邮箱](http://126.com)
3. [手机版新浪微博](http://weibo.cn)
4. [百度](https://www.baidu.com)
5. WebQQ by [opdss](https://github.com//opdss) 还有点问题
6. Webweixin by [opdss](https://github.com//opdss)
7. [微博网页版](http://weibo.com)
8. lantouzi by [opdss](https://github.com//opdss)

##Todolist
0. **重构代码，增加可扩展性**
1. 增加新浪微博网页版的登录 (已解决)
2. 增加 QQ 空间 和 QQ 邮箱的登录
3. 重新组织文件结构和代码风格，make it esay to read
4. 增加可扩展性，方便添加新的功能, 现在开发新功能的例子还很不优雅。

## tips of pull request 

欢迎大家一起来 pull request 

0. **请 pull request 到 fuck-login-dev 分支**
1. 增加新的网站登录
2. 改进错误, Python版本的兼容
3. 增加新的功能。一个开发新功能的例子: 
   <p>   
   1. xchaoinfo 想开发一个获取知乎某个问题所有回答者的点数
   2. xchaoinfo 新建一个文件叫做 get_star_by_xchaoinfo.py
   3. 然后他复制了原来 zhihu.py 文件，然后开发新的功能
   4. 最后 xchaoinfo 测试好了自己的代码, 然后 pull request
    </p>

## something 

0. 项目写了一段时间后，发现代码的风格和程序的易用性，可扩展性，代码的可读性，都存在一定的问题，所以接下来最重要的是重构代码，让大家可以更容易的做出一些自己的小功能。
1. 如果你觉得某个网站的登录很有代表性，欢迎在 issue 中提出，
如果网站的登录很有意思，我会在后面的更新中加入
2. 网站的登录机制有可能经常的变动，所以当现在的模拟的登录的规则不能使用的时候，请在 issue 中提出
如果时间允许的话，我会更新。