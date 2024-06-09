Software Stack
Docker 20.10.13
PHP 8.2.3
MySQL 8.1.0
Laravel 11
Swagger Api Documentation
Base Settings
Run git clone
Run cp .env.example .env
Set up your settings in .env:
DOCKER_NGINX_PORT
DOCKER_USERNAME
DOCKER_USER_ID
Run docker compose build
Run docker compose up -d
Run docker exec -it packages-app bash
Run composer install
Run php artisan key:generate
Run php artisan migrate
