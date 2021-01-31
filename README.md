# UziShop Application

UziShop app

## Features

- Comming soon

### Tech

- PHP 7.4.14

### Coding Rules

- Coding conventions: hhttps://www.php-fig.org/psr/

### Tools

- Adobe XD
- Font Awesome 5
- TSlint 6
- Prettier Standard 8

### Installation

Open your favorite Terminal and run these commands.

```sh
$ git clone git@github.com:VTNPlusD/uzi_shopping.git
$ cd uzi_shopping
% composer install
$ npm install
$ cp .env.example .env
```

### Setup mySQL Database

- For managing mySQL, click SQLite Browser: http://localhost:8686/phpmyadmin/server_databases.php
- Database setup

  Create a new database name `uzi_shopping`


### Config file .env

DB
```sh
DB_DATABASE=uzi_shopping
DB_USERNAME=root
DB_PASSWORD=
```

MAIL
```sh
MAIL_DRIVER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=noreplyshoppinglyn@gmail.com
MAIL_PASSWORD=Linh2510
MAIL_ENCRYPTION=tls
```

### Run app

Run

```sh
$ php artisan key:generate
$ php artisan config:clear
$ php artisan config:cache
$ php artisan migrate
$ php artisan db:seed
$ php artisan serve 
```

### Run the test

```sh
$ npm test
```

### Run the test coverage

```sh
$ npm run test -- --coverage --watchAll=false
```

- Open with live server in test-coverage/lcov-report/index.html
