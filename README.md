# subscribe_server
一个简单的本地股票数据订阅服务器
主要又3部分：
1、客户端，根据ID号请求数据
2、2个服务器：用于接收数据源的数据，转发给客户端，2个服务器间可以相互备份。
3、数据源：发送股票数据。

用到的内容：socket编程（tcp）,epoll i/o复用模型，多线程，线程池。



