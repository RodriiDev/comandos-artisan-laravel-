## Comandos artisan laravel

php artisan serve:  **arranca servidor laravel**

php artisan make:controller RegisterController: **Crea un controlador**

php artisan make:model Cliente: **crea un modelo**

php artisan make:migration create_nombre_tabla_table **Crear migración**

php artisan migrate: **Correr todas las migraciones**

php artisan migrate rollback: **Regresa las ultimas migraciones**

php artisan migrate rollback --step=5: **Regresa solo las ultimas 5** 

php artisan config:cache: **limpia caché**


php artisan migrate:refresh: **limpia toda la base de datos**

php artisan make:factory PostFactory: **Crear un factory**

php artisan tinker: **Para poder interactuar con la aplicacion y base de datos**

Post::factory()->times(200)->create(); **Correr factory**

php artisan make:policy PostPolicy --model=Post: **Crea Policy asociado a un Model**

php artisan route:cache: **Limpiar cache de rutas** 

php artisan route:list: **Lista las rutas**

php artisan make:component ListarPost: **Crear componente**

php artisan view:clear: **Limpiar vistas**

composer require livewire/livewire: **Instalar livewire**

php artisan make:livewire like-post: **Crea class y view en livewire**

npm run dev: **arranca servidor de desarrollo** 

composer create-project laravel/laravel mi-proyecto-laravel: **crear proyecto laravel**

