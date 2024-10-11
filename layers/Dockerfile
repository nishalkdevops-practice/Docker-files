# systemctl start status and all comes under this CMD command 
FROM almalinux:8 
RUN yum install nginx -y 
RUN echo "Welcome to the Docker world" > /usr/share/nginx/html/hello.html
RUN yum install git -y \
    && yum install maven -y 

RUN echo "helo world"

CMD [ "nginx","-g", "daemon off;" ]