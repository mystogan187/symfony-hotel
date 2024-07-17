# symfony-hotel
## Project Initialization

To clone the project along with its submodules, use the following command:

```sh
git clone --recurse-submodules https://github.com/mystogan187/symfony-hotel.git

```

## Requirements

- **MySQL**

DATABASE_URL="mysql://root:123@127.0.0.1:3306/hotel?charset=utf8"
```sh
php bin/console doctrine:database:create
php bin/console make:migration
php bin/console doctrine:migrations:migrate
```


- **Symfony CLI**: To install Symfony CLI, use:

```sh
curl -sS https://get.symfony.com/cli/installer | bash
```

## Start WebServer

To start the Symfony web server, use the following command:

```sh
symfony server:start
```