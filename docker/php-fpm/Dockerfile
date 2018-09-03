# PHP-FPM container based on phpdockerio/php-72-fpm
# DON'T USE IN PRODUCTION ENVIRONMENT
# =================================================================

FROM phpdockerio/php72-fpm:latest

WORKDIR "/application"

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update \
    && apt-get -y --no-install-recommends install php7.2-mysql php-xdebug php7.2-gd php-yaml \
    && apt-get clean; rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
