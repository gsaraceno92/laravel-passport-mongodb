## Introduction

Laravel Passport support for MongoDB projects using Jenssegers.

## Requeriments

Require library [Jenssegers/laravel-mongodb](https://github.com/jenssegers/laravel-mongodb)

## Official Documentation

Documentation for Passport can be found on the [Laravel website](http://laravel.com/docs/master/passport).

## Instalation

# Install requeriments

Installation using composer

```
composer require jenssegers/mongodb
```

See more in [Jessegers installation docs](https://github.com/jenssegers/laravel-mongodb#installation) for settings providers and database.

# Install Laravel Passport MongoDB

Installation using composer

```
composer require solucionatico/laravel-passport-mongodb
```

Follow the installation guide from [Laravel Passport installation docs](https://laravel.com/docs/5.6/passport#installation)

Except step for composer required :-D


Update AuthServiceProvider.php in app/Providers

Add line:

```
use Laravel\Passport\Passport;
```


## License

Laravel Passport is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
