## About Blade-Chirper

A simple application created based on Twitter.com, wherein 'chirps' emulate the action of tweets when posting content.

    * Tackle authentication features like login and registration using Laravel Breeze
    * Using resource controller to provide CRUD operations
    * Handle resource controller routing using route::resource()
    * User input is is validate using Laravel built in validation feature
    * Authorization is handle by applying model policy
    * Every post creted will have a notification trigger to all users

Built using blade. Simple, yet powerful templating engine that is included with Laravel.
Blade template files use the .blade.php file extension and are typically stored in the resources/views directory.

This application was developed to fulfill the requirements of my internship assignment.
## Deployment

Clone this directory then run:

```bash
composer install
```

## Prepare Environment File

Rename .env.example to .env

## Generate Application Key

```bash
php artisan key:generate
```

## Setup Database

configure database connection at .env file

## Run Migration

```bash
php artisan migrate
```

## Start Development Server

```bash
php artisan serve
```

## Security Vulnerabilities

If you discover a security vulnerability within this application, please send an e-mail to Aiman Bukhori via [emanbukhori@gmail.com](mailto:emanbukhori@gmail.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).


