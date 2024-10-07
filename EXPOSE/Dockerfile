FROM almalinux:8 
RUN yum install nginx -y 

#expose is not going to add any functionality it is just to expose the info

EXPOSE 80/tcp
CMD [ "nginx","-g", "daemon off;" ]