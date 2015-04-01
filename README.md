# tcp-proxy-demo
一个tcp代理服务器的demo

里面使用mysql作为示例，将本地mysql 3306端口映射到了本地4406端口，当然也可以将远程的msyql服务代理到本地。

## demo测试方法(假设本地有一个mysql服务端监听3306端口)

运行 php start.php start -d

使用mysql命令行测试 ```mysql -h127.0.0.1 -P4406 -pyour_password```
