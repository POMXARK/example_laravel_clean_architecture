Пример

### Linux Mint 21 

### Laravel v10.43.0 (PHP v8.2.15)

1. install php 8.2
2. sudo a2enmod php8.2
3. update-alternatives --set php /usr/bin/php8.2
4. https://getcomposer.org/download/
   2.7.1	2024-02-09
5. composer.phar
6. Временно перенести файлы из example_laravel_clean_architecture
7.  php ../composer.phar create-project laravel/laravel .
8. php artisan serve

### Install Sail

1. php composer.phar require laravel/sail --dev
2. php artisan sail:install
3. Which services would you like to install? (select pgsql)
4. sudo service mysql stop
5. ./vendor/bin/sail up
