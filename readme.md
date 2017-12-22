## Basic laravel passport api auth
[Laravel](https://github.com/laravel/laravel)
[Laravel Passport](https://github.com/laravel/passport)

- `git clone `
- `cd `
- `composer install`
- `php artisan migrate`
- `php artisan passport install`
- `php artisan serve`

### Available routes

- POST: `http://localhost:8000/api/register` params `name, email, password, c_password`
- POST: `http://localhost:8000/api/login` params `email, password`
- GET: `http://localhost:8000/api/user`
 