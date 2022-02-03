Laravel 8 Authentication using Jetstream with Inertia Js

### Steps

    Installation of Laravel Application
    Install Jetstream
    Create Auth with Inertia Js
    Installing Node Js Packages
    Laravel Migration
    Generated Scaffolding Files
    Application Testing

 Let’s get started – Laravel 8 Auth Scaffolding using Inertia Js Jetstream

 Installation of Laravel Application

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

## Install Jetstream
	$ composer require laravel/jetstream

## Create Auth with Inertia Js

	$ php artisan jetstream:install inertia

## Installing Node Js Packages

	$ npm install && npm run dev

## Laravel Migration

	$ php artisan migrate

Generated Scaffolding Files

When we open jetsream.php file, we will see ‘stack’ => ‘inertia’, because we are using inertia as stack.

Check These:-

Configuration Files at /app/config

Feature List of authentication module

Action Files at /app/Actions

Blade Template Files or scaffolding files at /resources/js


### Application Testing

	$ php artisan serve

Type on browser: 

URL- 127.0.0.1:8000	


In Last clicking on 'Login' & 'Register' links 

Register new user, then login


:+1:
