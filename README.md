# Docker PHP

Docker settings for setup PHP environment on httpd server with composer and xdebug.


## Setup
- Install docker-ce [https://docs.docker.com/install/](https://docs.docker.com/install/)
- Clone or download repository and run docker compose in the repository directory: `docker-compose up`

### Configured php extensions:
- zip
- pdo
- pdo_mysql
- mysqli
- gd

### Configured applications/libraries:
- libpng-dev
- libfreetype6-dev
- libjpeg62-turbo-dev
- nano
- composer
- php (7.2.x)
- apache2 (2.4.25)
