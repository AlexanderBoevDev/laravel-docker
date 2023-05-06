## Start project Laravel

Run the following commands

```
docker-compose up -d
```

```
docker exec -it laravel_app bash
```

```
composer install
```

```
php artisan key:generate
```

```
php artisan migrate
```

To exit the container, run the command

```
exit
```
---
Then follow the link: http://localhost/

---
If you want to see the structure of the database, as well as manage it, follow the link: http://localhost:8080/

---
Enter the login and password of the database from the env file.

Default login: root

And password: laravel

---
If you want to change the database data or some other data, then use the file.env in the root directory of the project.
