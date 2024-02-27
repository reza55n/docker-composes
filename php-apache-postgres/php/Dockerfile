FROM php:8.2-apache-bookworm
COPY ./*.conf /etc/apache2/
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
