from php:7.3.25-fpm-alpine3.11
RUN apk add --no-cache $PHPIZE_DEPS && pecl install xdebug-2.9.2 && docker-php-ext-enable xdebug
RUN docker-php-ext-install mysqli pdo pdo_mysql && docker-php-ext-enable pdo_mysql
