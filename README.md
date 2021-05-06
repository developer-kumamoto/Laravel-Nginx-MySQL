# Laravel-Nginx-MySQL
For development starter kit.

## How to use.

1. Create Laravel project.
   ```
   docker-compose run --rm acl_composer composer create-project --prefer-dist laravel/laravel .
   ```
2. Change storage permission.
   ```
   docker-compose run --rm acl_app chmod go+w -R storage
   ```