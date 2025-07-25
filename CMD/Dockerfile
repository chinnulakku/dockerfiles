FROM almalinux:8
RUN yum install nginx -y 
RUN systemctl stop nginx
CMD ["nginx","-g","daemon off;"]