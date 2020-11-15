FROM centos:centos7

RUN yum -y install httpd

COPY ./html/ /var/www/html/

CMD ["/usr/sbin/httpd","-DFOREGROUND"]



# ubuntu + nginxでやろうとしたけど、上手く行かず、、、
# FROM ubuntu:latest

# RUN apt-get update && apt-get install -y nginx

# COPY ./html /usr/share/nginx/html

# EXPOSE 80

# # ENTRYPOINT [ "nginx" ]
# CMD ["nginx", "-g", "daemon off;"]