# Application for manage Jobs.


# Instal the Server mysql with:
```bash
docker run --name mysql -e MYSQL_ROOT_PASSWORD=123456  -p 3306:3306 -d mysql:latest
docker exec -it mysql bash
mysql -uroot -p123456
ALTER USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY '123456';
FLUSH PRIVILEGES
CREATE DATABASE jobpostr;
quit
exit
```

# Run the application with:


```js
adonis serve --dev
```
