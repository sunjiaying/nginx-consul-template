# nginx-consul-template

此项目基于liberalman的ginx-consul-template做了些许的调整：

在consul-template.service文件中添加了，通过环境变量获取consul server的IP，并在Dockerfile设置了consul_server_ip环境变量参数

用于学习和测试consul-template与nginx

生成镜像

docker build -t sunjiaying/nginx-consul-template .

