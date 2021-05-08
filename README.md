# Laravel-Nginx-MySQL
For laravel development starter kit.

## How to use.
1. Checkout
2. Create Laravel project.
   ```
   docker-compose run --rm laravel_composer composer create-project --prefer-dist laravel/laravel .
   ```
3. Change storage permission.
   ```
   docker-compose run --rm laravel_app chmod go+w -R storage
   ```
4. Change DATABASE settings in .env file.
5. Start.
   ```command:powershell
   docker-compose up -d laravel_app laravel_db laravel_web
   ```
6. Access localhost:8888