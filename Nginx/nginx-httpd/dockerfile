FROM centos:7
RUN yum install httpd -y
COPY index.html /var/www/html/index.html
COPY proxy.conf /etc/httpd/conf.d/proxy.conf
CMD ["httpd", "-DFOREGROUND"]
