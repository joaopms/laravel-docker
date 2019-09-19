# laravel-docker
Dockerized Laravel environment with PHP, nginx and MariaDB.

## How to run
- Copy `config.example.env` to `config.env` and tweak to your liking
- `docker-compose up -d`
- Open http://localhost:8080

## Database administration
- `docker-compose exec mariadb mysql -u laravel -p`

## Used Ports
`8080`: nginx
`9000`: php-fpm
`3306`: MariaDB