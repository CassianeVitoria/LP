# LP
curl -s "https://laravel.build/LP?with=mysql" | bash

cd LP
./vendor/bin/sail up
./vendor/bin/sail artisan migrate

breeze
composer require laravel/breeze --dev
php artisan breeze:install


sail
php artisan migrate

vendor/laravel/framework/scr/Illuminate/Http/Middleware/trusproxies.php
protected $proxies='*';

Criar
php artisan make:model -mrc cliente

php artisan make:migration create_users_table

php artisan make:migration create_users_table --create=users

executar

php artisan migrate

