# SeleniumSpider
利用Selenium对文献网站进行简单的doi查询
该程序分为服务端和客户端，客户端写点简单的ui并对我服务器发送一个请求，在ui中通过点击绑定的事件，他会通过一request函数访问我服务器的地址，并在url上加上要搜索的文章标题，要搜索的文章标题从文本框中获得即可，收到服务器的响应就弹出一个弹窗来显示出这个查询结果，也就是doi.
服务端就是拿到search的关键词然后调用手工模拟的方法进行搜索，selenium会帮我们操作浏览器，实现对打开的标签中的元素点击，输入值，查找 
