# paekdusan
paekdusan是一个跨平台的简易C++服务框架，并且附带了实现了静态页面的webserver

代码比较依照[吴导](https://github.com/yanyiwu)的hpp风格写的

其中socket部分使用了预编译宏的方式来实现了windows和linux的跨平台

其中用到的Log函数来源于[Limonp](https://github.com/yanyiwu/limonp)

其中用到的BlockingBoundedQueue来源于[muduo](https://github.com/chenshuo/muduo/)，但是改用了C++11的mutex和condition以实现跨平台

其中用到的ThreadPool来源于[Limonp](https://github.com/yanyiwu/limonp)，但是改用了C++11的thread以实现跨平台

## 依赖
编译器支持C++11

## 参考
主要参考的源码

- [tinyhttpd](http://sourceforge.net/projects/tinyhttpd/)
- [LightCgiServer](https://github.com/imyouxia/LightCgiServer)
- [husky](https://github.com/yanyiwu/husky)

主要参考的文章

- [RFC2616](http://www.ietf.org/rfc/rfc2616.txt)
- [tinyhttpd源码剖析](http://armsword.com/2014/10/29/tinyhttpd-code-analyse/)
- [写了一个简单的CGI Server](http://armsword.com/2014/05/18/light-cgi-server/)
- [tinyhttpd源码分析](http://blog.sina.com.cn/s/blog_a5191b5c0102v9yr.html)
- [http协议中content-length 以及chunked编码分析](http://blog.csdn.net/yankai0219/article/details/8269922)
- [HTTP协议头部与Keep-Alive模式详解](https://www.byvoid.com/blog/http-keep-alive-header/)
- [C++11中多线程并发的实践](http://www.cnblogs.com/haippy/)
- [Threads and fork(): think twice before mixing them](http://www.linuxprogrammingblog.com/threads-and-fork-think-twice-before-using-them)    

更多信息

[paekdusan](http://cstdlib.com/tech/2015/05/17/http-and-web-server/)
