# Accent
three type user login( user,manager,admin). user only can reading and comment this topic &amp; manager can manage post ,create-update post etc.

Project Accent

Create Project:
composer create-project  --prefer-dist  laravel/laravel accent
Going to Location:
cd c:\XAMPP\htdocs\Laravel
cd accent
Edit User Migration & Migrate:
php artisan migrate
for creating user login
composer require laravel/ui 

php artisan ui bootstrap --auth 

npm install

npm run dev

Checking User
php artisan make:middleware UserAccess


php artisan make:seeder CreateUsersSeeder

php artisan make:model Comment –m
php artisan make:model Post –m
php artisan migrate


php artisan make:controller PostController –resource

php artisan make:controller BlogController –resource
php artisan make:controller CommentController –resource


config/database 'strict' => true this true position write false, // that is true


php artisan make:controller UserController –resource

........................................
