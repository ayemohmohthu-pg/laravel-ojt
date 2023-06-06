# LaravelOJT

### 1. Cloning project to PC

From terminal or command line, run the following command
 ```
 git clone https://github.com/ayemohmohthu-pg/laravel-ojt.git
 ```

### 2. Pull source from develop
```
cd laravel-ojt
git checkout main
git pull origin main
```

### 3. Add .env file in sharingengine>laravel-app>.env
```
cp laravel-app/.env.local laravel-app/.env
```
 
### 4. Create/start container in docker
```
docker-compose up -d
```

### 5. Enter to PHP container & Laravel App and run migrate command
```
docker-compose exec app bash
cd laravel-app
composer install
php artisan migrate
```

### 6. Run laravel app on browser

http://localhost:8000/

test for multiple template
