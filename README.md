# Задание 1
В каждом из трех приложений попробуйте найти - что нужно изменить, чтобы сменить текст на главной странице?
* [yii2](https://github.com/scriptius/yii2_test/commit/c08c1dbf1e20f691a1eee8250b06bc7807eb609b)
* [symfony](https://github.com/scriptius/symfony.test/commit/a475a961055e4838750baaf7591e9d57ab517b14)
* [laravel](https://github.com/scriptius/laravel.test/commit/fc63026b2bba21d73ad2eb46a6e9d9cda85bfbe2)

# Задание 2
## Yii2
1. Создал middleware ```php artisan make:middleware CheckAuth```
2. Прописал обработчик handle https://github.com/scriptius/laravel.test/blob/hw2/app/Http/Middleware/CheckAuth.php#L16
3. Добавил обработчик в список https://github.com/scriptius/laravel.test/blob/hw2/app/Http/Kernel.php#L19
