# What is it?
- Simple laravel application that built on LAMP stack (Laravel (Run on PHP-FPM), Nginx, Mysql, PHP)
## How to run
- Run command
```bash
docker compose up -d 
```

- Access localhost or your server id (PORT 80)

- Connect mysql
```bash
docker compose exec db mysql -uroot -p123456
```

- Access tinker (PHP laravel REPL to access directly into whole laravel application)
```bash
docker compose exec app php artisan tinker
```

[Tutorial](https://www.digitalocean.com/community/tutorials/how-to-set-up-laravel-nginx-and-mysql-with-docker-compose)
