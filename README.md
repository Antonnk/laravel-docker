# Laravel Docker simple starter template

php-apache server with php8, npm and yarn.

`$ docker compose build`

`$ docker compose up`

`$ docker compose exec php-apache bash`

---

Database config

```
DB_CONNECTION=pgsql
DB_HOST=database
DB_PORT=5432
DB_DATABASE={docker-compose.POSTGRES_DB}
DB_USERNAME=postgres
DB_PASSWORD=secret
```
