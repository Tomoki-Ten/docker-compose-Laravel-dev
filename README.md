# docker-compose-Laravel-dev
These files are so that I create something in local environment.

After clone this repository,

You need to do some commands below to make this work collectly.

------------------------------------------------------------------
Command following the order.

1. composer install in php container to create vender files in backend directory.

2. cp .env.example .env in order to set your Laravel, because this repository does not have .env file
   when you buid this with docker-compose command, so you need to do this process.
  
3. php artisan key:generate to create APP_KEY in .env file

------------------------------------------------------------------
