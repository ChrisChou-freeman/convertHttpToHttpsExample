about
-----------------------------

This project is to show how to transfer http requests to https

Please use a virtual host to access the page, for example, configure the host as

```text
127.0.0.1 localhost.com

```
After running the project, it will monitor port 80 and port 443 at the same time, and the request connected to port 80 will be redirected to port 443

关于
-----------------------------

这个项目是为了展示如何将http的请求转入到https

请用虚拟host访问页面，比如配置host为

```text
127.0.0.1 localhost.com

```
运行项目后将会同时监听80端口和443端口，并将80端口的请求跳转到443端口
