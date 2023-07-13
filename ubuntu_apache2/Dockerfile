FROM ubuntu:focal

RUN apt-get update
RUN apt-get install -y apache2 git

EXPOSE 80

CMD ["/usr/sbin/apache2", "-D", "FOREGROUND"]
