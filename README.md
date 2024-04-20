# SII - Situacion Tributaria (Laravel)

Controlador para consultar situación tributaria de terceros.

Puedes copiar directamente el archivo donde se situan los controladores o puedes ejecutar el siguiente comando y luego copiar el contenido del archivo:

```shell
php artisan make:controller ApiSiiController 
```

Tambien puedes hacer una prueba rapida para probar el controlador agregando la siguiente ruta:

```php
Route::get('/sii/prueba', [ApiSiiController::class, 'prueba']);
```

El response tiene el siguiente formato:

![image](https://github.com/Skeiceee/sii_situacion_tributaria_laravel/assets/12854219/8de017b1-12e3-4ddd-a818-56ea07f0145a)


