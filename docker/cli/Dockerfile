FROM klabs/php_cli:7.2
MAINTAINER Kaliop

USER root
RUN apt-get update && DEBIAN_FRONTEND=noninteractive sudo apt-get install -y \
    php-xdebug php7.2-redis
USER site
