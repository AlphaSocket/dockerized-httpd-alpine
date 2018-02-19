# Alphasocket/dockerized-httpd-alpine
#### httpd-alpine
Dockerized httpd service on alpine distro (FROM httpd:latest)


| [![Build Status](https://semaphoreci.com/api/v1/alphasocket/dockerized-httpd-alpine/branches/latest-dev/badge.svg)](https://semaphoreci.com/alphasocket/dockerized-httpd-alpine) | Size / Layers | Version |
| ----- | ----- | ----- |
| Dev image | [![](https://images.microbadger.com/badges/image/03192859189254/dockerized-httpd-alpine:latest-dev.svg)](https://microbadger.com/images/03192859189254/httpd-alpine:latest-dev ) | [![](https://images.microbadger.com/badges/version/03192859189254/dockerized-httpd-alpine:latest-dev.svg)](https://microbadger.com/images/03192859189254/httpd-alpine:latest-dev) |
| Prd image | [![](https://images.microbadger.com/badges/image/alphasocket/httpd-alpine:latest-dev.svg)](https://microbadger.com/images/alphasocket/httpd-alpine:latest-dev ) | [![](https://images.microbadger.com/badges/version/alphasocket/httpd-alpine:latest-dev.svg)](https://microbadger.com/images/alphasocket/httpd-alpine:latest-dev) |

## Branches & Versions
- latest
- latest-dev


## Packages installed


## Configurable envvars
~~~
CONFIG_REDINESS_TEST="true"
CONFIG_LIVENESS_TEST="true"
CONFIG_GROUPS_ADDITIONAL_NAME=""
CONFIG_GROUPS_MAIN_NAME="www-data"
CONFIG_USERS_ADDITIONAL_NAME=""
CONFIG_USERS_ADDITIONAL_GROUPS=""
CONFIG_USERS_MAIN_NAME="www-data"
CONFIG_USERS_MAIN_GROUPS="www-data"
CONFIG_HTTPD_SERVERNAME="httpd-alpine"
CONFIG_HTTPD_ALIAS="httpd-alpine"
CONFIG_HTTPD_TIMEOUT="1000"
CONFIG_HTTPD_DOCUMENT_ROOT="/var/www/html"
CONFIG_HTTPD_DOCUMENT_INDEX="index.php"
CONFIG_HTTPD_DOCUMENT_OPTIONS="FollowSymLinks"
CONFIG_PHP_PROXY_TIMEOUT="100"
CONFIG_PHP_PROXY_REGEX=".+\.ph(p[3457]?|t|tml)$"
CONFIG_PHP_FPM_HOST="php-fpm.service"
CONFIG_PHP_FPM_PORT="9000"
CONFIG_PATHS_CONTAINER_STATUS="/tmp/container_status"
CONFIG_PATHS_TEMPLATES_HTTPD_USER_GROUP="/usr/local/templates/05-user-group.conf"
CONFIG_PATHS_TEMPLATES_HTTPD_SERVER="/usr/local/templates/10-server.conf"
CONFIG_PATHS_TEMPLATES_HTTPD_SSL="/usr/local/templates/10-ssl.conf"
CONFIG_PATHS_TEMPLATES_HTTPD_FASTCGI="/usr/local/templates/20-fastcgi.conf"
CONFIG_PATHS_TEMPLATES_HTTPD_VHOST_DEV="/usr/local/templates/dev_vhost.conf"
CONFIG_PATHS_TEMPLATES_HTTPD_VHOST_PRD="/usr/local/templates/prd_vhost.conf"
CONFIG_PATHS_CONF_HTTPD_USER_GROUP="/usr/local/apache2/conf/conf.d/05-user-group.conf"
CONFIG_PATHS_CONF_HTTPD_SERVER="/usr/local/apache2/conf/conf.d/10-server.conf"
CONFIG_PATHS_CONF_HTTPD_SSL="/usr/local/apache2/conf/conf.d/10-ssl.conf"
CONFIG_PATHS_CONF_HTTPD_FASTCGI="/usr/local/apache2/conf/conf.d/20-fastcgi.conf"
CONFIG_PATHS_CONF_HTTPD_VHOST="/usr/local/apache2/conf/vhost.d/main.conf"
~~~
