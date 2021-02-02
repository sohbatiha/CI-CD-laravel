FROM php:7.4-fpm

RUN apt-get update && apt-get install -y \
    curl \
    zip \
    unzip


RUN docker-php-ext-install pdo_mysql unzip



EXPOSE 9000
CMD ["php-fpm"]
