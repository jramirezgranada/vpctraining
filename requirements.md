# Laravel Requirements Dependencies

## Required

- php7.0 >
- mysql server

## PHP Packages
- php7.0
- php7.0-zip
- php7.0-dom
- php7.0-mcrypt
- php7.0-common
- php7.0-json
- php7.0-mbstring
- php7.0-mysql
- php7.0-xml

## After checkout

- `composer install`
- `cp .env.example .env`
- `sudo chmod -R 775 storage boostrap/cache`
- `php artisan key:generate` 
