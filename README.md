#

## Install PHP, Composer and Laravel

composer global require "laravel/installer"

## Create Laravel App

laravel new blog --jet --teams --prompt-jetstream

cd blog
php artisan key:generate
php artisan migrate

php artisan serve

## Copy Bootstap Template

Copy the Bootstrap Template files to subfolder resources\views\blog

