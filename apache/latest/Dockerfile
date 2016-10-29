FROM httpd:2.4
RUN mkdir -p /var/www/html/static

# For Virtualbox user
RUN usermod -u 1000 www-data

COPY ./custom-httpd.conf /usr/local/apache2/conf/httpd.conf
