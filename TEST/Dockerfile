FROM almalinux:8

RUN yum update -y

RUN yum install nginx -y

RUN rm -rf /usr/share/nginx/html/index.html

RUN echo "Welcome to the Docker world" > /usr/share/nginx/html/index.html

ENTRYPOINT [ "nginx","-g", "daemon off;" ]