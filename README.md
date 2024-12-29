<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

## Laravel simple CRUD 

A simple CRUD (Create, Read, Update, Delete) application built using Laravel 11. This project demonstrates fundamental Laravel functionalities such as routing, request handling, validation, database operations, and pagination.

## Features

Create, Read, Update, and Delete posts.
Server-side validation with custom error messages.
Pagination for posts listing.
Tailwind CSS for modern and responsive UI design.

## Installation Steps

1. Clone the Repository:

```
git clone https://github.com/your-username/laravel-crud.git
cd laravel-crud

```


2. install Dependencies:

```
composer install

```

3. Copy the .env.example file and rename it to .env:
```
cp .env.example .env
```

4. Generate Application Key:
```
php artisan key:generate
```
5. Run Migrations and Seed Database:
```
php artisan migrate --seed
```

6. Start the Development Server:
```
php artisan serve

```