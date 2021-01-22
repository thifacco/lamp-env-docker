# Ambiente LAMP com DOCKER
Ambiente de desenvolvimento Linux - Apache - MySQL - PHP-FPM

## Requisitos
1. Instalar o [Docker Desktop](https://www.docker.com/products/docker-desktop)

## Iniciar os containers
```
cd lamp-env-docker
docker-compose up -d
```

## Conectar no MySQL pelo container
```
docker-compose exec mysql bash
cd /bitnami/mysql
mysql -u root -p
[senha em branco]
```

## Referências
- [PHP-FPM](https://hub.docker.com/r/bitnami/php-fpm)
- [APACHE](https://hub.docker.com/r/bitnami/apache)
- [MySQL](https://hub.docker.com/r/bitnami/mysql)
