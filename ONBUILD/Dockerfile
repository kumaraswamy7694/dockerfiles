FROM almalinux:8
#same as centos
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/hello.html
ONBUILD ADD index.html /usr/share/nginx/html/index.html
CMD ["nginx" , "-g", "daemon off;"]
