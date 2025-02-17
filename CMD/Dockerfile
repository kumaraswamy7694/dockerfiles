FROM almalinux:8
#same as centos
RUN yum install nginx -y
RUN echo "hello, welcome to docker file a way of creating own images" > /usr/share/nginx/hello.html
CMD ["nginx" , "-g", "daemon off"]
#daemon off command makes our container running and attach to the screen.