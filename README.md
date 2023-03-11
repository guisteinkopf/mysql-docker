# Docker Mysql

#### Como usar ?
```
docker-compose up -d
```
#### Para ter acesso atraves de outros containers
```
docker-compose exec mysql mysql -psecret -e "ALTER USER 'laravel'@'%' IDENTIFIED WITH mysql_native_password BY 'secret';"
```