# WordPress docker config

## How to use
1. Rename `config-sample.env` to `config.env`
2. Change the following values:
    - `WORDPRESS_DB_USER` and `MYSQL_USER` to set up database user name
    - `WORDPRESS_DB_NAME` and `MYSQL_DATABASE` to set up database name
    - `WORDPRESS_DB_PASSWORD` and `MYSQL_PASSWORD`  to set up database password
3. (Recomended) Add additional WordPress config values(WORDPRESS_AUTH_KEY, WORDPRESS_SECURE_AUTH_KEY, WORDPRESS_LOGGED_IN_KEY ant etc.) to `config.env`
4. Run `docker-compose up -d`
5. Visit `http://localhost:8080`