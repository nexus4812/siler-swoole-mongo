FROM phpswoole/swoole:5.0.1-php8.2-dev

RUN pecl install mongodb && \
    docker-php-ext-enable mongodb opcache

COPY ./docker/php/php.ini /usr/local/etc/php/php.ini
