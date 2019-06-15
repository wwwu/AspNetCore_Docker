#定义基础镜像 nginx:latest
FROM nginx
#复制自定义的配置文件到Nginx配置文件目录下
COPY helloworld.conf /etc/nginx/conf.d/helloworld.conf
#暴露80端口到外部
EXPOSE 80
#容器运行参数
CMD ["nginx", "-g", "daemon off;"]