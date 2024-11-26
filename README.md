<div align='center'>

# Short URL Generator

</div>


## Configuration
- PHP-8.1
- Laravel-10

## How to run this project

### ENV Setup 
- Please create `.env` file and copy-paste data from the `.env.example` file.
- You have to setup database related credentials properly in .env


### Update Your Composer 
```bash
composer update
```

### Generate APP_KEY
```bash
php artisan key:generate
```

### Migrate 
<h5>Just run this command</h5>

```bash
php artisan migrate
```

### Seeder
```bash
php artisan db:seed
```

### Run Project 
```bash
php artisan serve
```


## Test Case Result 
Just run the command
```bash
php artisan test
```

<img src="">


### Visit Page

- Home Page : http://127.0.0.1:8000

<img src="">

<br>


### Packages used in application
- #### [Artisan View](https://github.com/svenluijten/artisan-view)
- #### [Laravel Pint](https://github.com/laravel/pint)
- #### [PEST Framework](https://pestphp.com)
