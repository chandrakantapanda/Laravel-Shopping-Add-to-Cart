<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel Shopping Add to Cart 

After clone you can run it

### how to achieve follow a few steps 
Getting Started
1. Clone the repository and install composer packages by running:
```bash
composer update 
```
2. Create .env file from env.example
```bash
copy .env.example .env
```
4. Generate Application Key for your application.
```bash
php artisan key:generate
```
5. Run migration for create users table, admins  tables :
otherwise import the db file to your local db
```bash
php artisan migrate --seed
```
6. Run your Laravel application
```bash
    php artisan serve
```
7. Go to http://127.0.0.1:8000/ 