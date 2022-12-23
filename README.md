## MySql
```
PORT: 33060
MYSQL_DATABASE: maon_db
MYSQL_ROOT_PASSWORD: root
MYSQL_ROOT_USER: root

```
## Step install project laravel

### Install composer
```
composer install
After run check version composer : composer --version

```
### Install Laravel
```
composer create-project laravel/laravel {name_project}
e.g: composer create-project laravel/laravel example-app

```


## Run docker compose

```
docker compose build
docker compose up -d

```
## Remove "Public" from URL
```
1. The first step is, Rename server.php in your Laravel root folder to index.php
2. Copy the .htaccess file from /public directory to your Laravel root folder.
```
## Launch App
### System
```
http://localhost/

```
