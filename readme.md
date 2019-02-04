1. Follow 1 to 5 steps from [previous project](https://github.com/rockysynergy/laravel_album) to set things up
* use `php artisan make:controller ItemsController --resource` to generate functons
2. Use `Postman` for API Testing
3. Set csrf token in `App\Http\Middleware\VerifyCsrfToken`

```php
protected $except = [
    'api/*'
];
```
4. `public/be/index.html` is the front end item resource manager
5. use `laravel-cors`
