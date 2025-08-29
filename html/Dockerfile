FROM ubuntu
LABEL author="mah" maintainer="mah" version="1.0" description="nginix web server from ubuntu"
RUN apt update -y
RUN apt install nginx -y
EXPOSE 80
COPY . /var/www/html/index.html
ENTRYPOINT [ "/usr/sbin/nginx", "-g", "daemon off;" ]