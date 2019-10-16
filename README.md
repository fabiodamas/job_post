# Application for manage Jobs.


# Instal o Server mysql with:
```bash
docker run --name mysql -e MYSQL_ROOT_PASSWORD=123456  -p 3306:3306 -d mysql:latest
docker exec -it mysql bash
mysql -uroot -p123456
create database jobpostr;
quit
exit
```

# Run the application with:


```bash
adonis serve --dev
```
