FROM ubuntu:focal
ENV DEBAIN_FRONTEND=nointeractive
RUN apt-get update
RUN apt-get install -y apache2 git
RUN git clone https://github.com/AnByoungHyun/static-web-template.git 
EXPOSE 80

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
