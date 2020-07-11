# docker-php-nginx-postgres-composer

Конфигурация Docker Compose для запуска PHP 7.4 с Nginx, PHP-FPM, PostgreSQL 10.1

## Обзор


* web (Nginx)
* php (PHP 7.4 with PHP-FPM)
* postgres (PostgreSQL 10.1)
* adminer (Adminer 4.7.7)

## Предпосылки

На данный момент проект был протестирован только на Linux, но должен нормально работать на Windows и на Mac.

### Запуск
Запуск контейнеров ```make start```
Работа с "composer" ```make install```
Проект устанавливается в папку src


