FROM centos:centos7
RUN mkdir /app/
ADD index.html /app/index.html
RUN yum -y install epel-release
RUN yum -y install nginx
RUN usermod -u 1001 nginx && groupmod -g 1001 nginx
ADD nginx.conf /etc/nginx/nginx.conf
EXPOSE 8000
CMD ["nginx", "-g", "daemon off;"]
