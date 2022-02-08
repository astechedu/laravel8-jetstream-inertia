<img src="https://laravelnews.s3.amazonaws.com/images/jetstream-banners.jpeg" width="300" height="200">

# Laravel 8 Authentication using Jetstream with Inertia Js

### Steps

    1. Installation of Laravel Application
    2. Install Jetstream
    3. Create Auth with Inertia Js
    4. Installing Node Js Packages
    5. Laravel Migration
    6. Generated Scaffolding Files
    7. Application Testing

 Let’s get started – Laravel 8 Auth Scaffolding using Inertia Js Jetstream

## 1. Installation of Laravel Application

 ### By Laravel Installer

	$ composer global require laravel/installer
	$ laravel
	$ laravel new blog

### By using composer	
	$ composer create-project --prefer-dist laravel/laravel blog
	$ php artisan serve

This command outputs:-

	Starting Laravel development server: http://127.0.0.1:8000

Assuming laravel already installed at system.

Database also configured with application.

## 2. Install Jetstream
	$ composer require laravel/jetstream

## 3. Create Auth with Inertia Js

	$ php artisan jetstream:install inertia

## 4. Installing Node Js Packages

	$ npm install && npm run dev

## 5. Laravel Migration

	$ php artisan migrate

## 6. Generated Scaffolding Files

When we open jetsream.php file, we will see ‘stack’ => ‘inertia’, because we are using inertia as stack.

Check These:-

Configuration Files at /app/config

Feature List of authentication module

Action Files at /app/Actions

Blade Template Files or scaffolding files at /resources/js


### 7. Application Testing

	$ php artisan serve

Type on browser: 

URL- 127.0.0.1:8000	


In Last clicking on 'Login' & 'Register' links 

Register new user, then login


:+1:
