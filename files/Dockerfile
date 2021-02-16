FROM registry.access.redhat.com/ubi8/ubi:latest
RUN yum -y install httpd
EXPOSE 80
CMD ["/usr/sbin/httpd", "-D", "FOREGROUND"]
