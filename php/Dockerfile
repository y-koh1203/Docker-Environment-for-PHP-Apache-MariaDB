FROM php:7.3.0-apache-stretch

COPY php.ini /usr/local/etc/php/

# install composer
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer