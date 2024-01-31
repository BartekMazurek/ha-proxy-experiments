# Ha-proxy experiments

> Simple HA-PROXY scenario with load balanced multiple instances of PHP, NGINX & POSTGRES

## 1 - How to setup
> docker-compose up -d

## 2 - How to test WEB
> Type **localhost:80** or **localhost:81** as URL in browser & refresh page multiple times

## 3 - How to test DB
> Connect multiple times into DB through terminal with PSQL: **psql -h [IP] -p 5432 -U proxy -d proxy_db**