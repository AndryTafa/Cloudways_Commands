
if using something like fluxui.dev
```
composer require laravel/sanctum
```
```
php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
```

and then:
```
composer install
```

```
php artisan cache:clear && php artisan config:clear && php artisan route:clear && php artisan view:clear
```

```
php artisan migrate
```

```
npm install
```

```
npm run build
```

```
chmod -R 775 storage bootstrap/cache
```

```
composer dump-autoload
```
