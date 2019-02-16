<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

```bash
    php aritsan make:controller BlogController -r
    php artisan make:resource Blog
    add route inside routes/api.php
    ex: api/blogs
        Route::get('blogs', 'Api\BlogController@index')->name('api.blogs.index');
```
