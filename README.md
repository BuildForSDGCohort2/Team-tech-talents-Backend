# Team-tech-talents-Backend

Comes with:
- web-app: `Laravel/PHP-7.2`
- web-server: `Nginx:alpine`
- database: `Mysql-5.7.22`

## Setup
- `https://github.com/BuildForSDGCohort2/Team-tech-talents-Backend`
- `cd laravel-docker-master`
- `docker-compose up -d`
- `docker exec app composer install`
- `cp .env.example .env`
- `docker-compose exec app php artisan key:generate`

Now that all containers are up, we can add `127.0.0.1 project.local` to our `/etc/hosts` file

Boom! access `project.local` on your favorite browser