FROM ubuntu
WORKDIR /var/www/html/
RUN apt-get update
RUN apt-get install -y vim nginx
EXPOSE 80
COPY index.html kimmi-blue.svg /var/www/html/
CMD ["nginx", "-g", "daemon off;"]
