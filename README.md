# e-commerse-vue-laravel
Normal e-commerse website using in laravel/vue js

# laravel installation (laravel-backend)
https://laravel.com/
composer create-project --prefer-dist laravel/laravel

# laravel requiremnt 
https://laravel.com/docs/10.x/sanctum#spa-configuration
https://laravel.com/docs/10.x/starter-kits#laravel-breeze

composer require laravel/breeze --dev
php artisan breeze:install api
php artisan migrate
php artisan optimize:clear
php artisan serve

# vue installation (vue-frontend-api)
https://vuejs.org/

https://router.vuejs.org/installation.html
  npm install vue-router@4
https://pinia.vuejs.org/getting-started.html
  npm install pinia
npm install axios
