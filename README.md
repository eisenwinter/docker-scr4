# docker-scr4

Für SCR4 inkludiert nginx, mariadb, adminer und php (+xdebug, mysql pdo und redis driver)

Runterladen, entzippen, im Verzeichnis `docker-compose up`

das Unterverzeichnis `public` wird vom Server 'geserved'

## Übersicht

| Service  | Port |
|----------|------|
| MardiaDB | 3306 |
| NginX    | 6969 |
| Adminer  | 8080 |
| XDebug   | 9000 |

php.ini lässt sich unter `configs/php/php-ini-overrides.ini` anpassen

nginx config lässt sich unter `configs/nginx/nginx.conf` anpassen

## Passwörter

*mariadb* 

root : scr4
user : scr4

