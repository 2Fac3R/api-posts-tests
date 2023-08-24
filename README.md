# api-posts-tests
## Description

This project is centered around the development of a RESTful API, serving as an illustrative example of its functioning using Posts. For testing purposes, only the tests have been implemented, without any additional features.

Stack:

* PHP (7.3) + Laravel (6)

## Installation

Clone the repository

    git clone https://github.com/2Fac3R/api-posts-tests.git

Switch to the repo folder

    cd api-posts-tests

Install all the dependencies using composer

    composer install

Rename ".env.example" to ".env" and add your database settings.
    
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=<your-database>
    DB_USERNAME=<your-username>
    DB_PASSWORD=<your-password>

Run migrations

    php artisan migrate

Run tests

    ./vendor/bin/phpunit
  

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Any feedback is appreciated.
