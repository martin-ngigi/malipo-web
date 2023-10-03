

## Controllers:
```
php artisan make:controller /API/V1/AuthController

```

## Models:
```
php artisan make:model Category -m
```


### clear machine cache:
- in the terminal, run:
```
php artisan optimize:clear
php artisan config:clear
php artisan route:clear
php artisan route:cache
php artisan config:cache
php artisan cache:clear
composer dump-autoload
php artisan view:clear
```