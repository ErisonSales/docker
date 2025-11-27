FROM phpdockerio/php:8.4-fpm
WORKDIR "/application"

RUN apt-get update \
    && apt-get -y --no-install-recommends install \
        php8.4-gd \
        php8.4-imagick \
        php8.4-ldap \
        php8.4-intl \
        php8.4-mcrypt \
        php8.4-mysql \
        php8.4-redis \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
