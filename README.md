# Twitter Clone (twitter-clone)

### Tutorial showing you how to build Twitter

If you'd like a step by step guide on how to build this just **CLICK THE IMAGE BELOW**

## App Setup

```
composer install 

cp .env.example .env 

php artisan cache:clear 

composer dump-autoload 

php artisan key:generate

composer require laravel/breeze --dev

php artisan breeze:install vue --ssr

php artisan serve
```

Create the DB
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=twitter-clone
DB_USERNAME=root
DB_PASSWORD=
```
Now migrate your DB
```
php artisan migrate

php artisan db:seed
```

Now run this command to start the project 
```
npm i

npm run dev
```

