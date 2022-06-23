# php-8.1-alpine
Docker image with php-8.1.7-alpine

All image contain following php extension graphviz and composer.

- bcmath
- gd
- intl
- json
- libxml
- mbstring
- openssl
- PDO
- pdo_pgsql
- pdo_mysql
- SimpleXML
- tokenizer
- Zend OPcache
- amqp
- redis
- apcu
- yaml
- zip
- curl
- zip 
- exif
- iconv

## Image Variants
### php-8.1-alpine:cli
This use the cli base image 

### php-8.1-alpine:npm
This use the cli base image also contain nodejs and npm and xdebug

### php-8.1-alpine:fpm or php-8.1-alpine:latest
This use the fpm base image and contain the wkhtmltopdf with patched QT build binary

### php-8.1-alpine:dev
This use the fpm base image and contain the wkhtmltopdf with patched QT build binary and xdebug
