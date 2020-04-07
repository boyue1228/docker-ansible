FROM alpine:3.11.5
MAINTAINER """
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'default nginx page' \
> /usr/share/nginx/html/index.html
EXPOSE 80