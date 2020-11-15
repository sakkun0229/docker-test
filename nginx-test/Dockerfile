FROM ubuntu:latest

RUN apt-get update && apt-get install -y nginx

COPY ./html /usr/share/nginx/html

EXPOSE 80

ENTRYPOINT ["nginx", "-g"]
