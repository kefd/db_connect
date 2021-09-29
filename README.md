# db_connect
django

mariadb
```bash
$ mysql -u root -p
$ CREATE DATABASE <myproject> CHARACTER SET UTF8;
$ CREATE USER <myprojectuser@localhost> IDENTIFIED BY '<password>';
$ GRANT ALL PRIVILEGES ON <myproject>.* TO <myprojectuser@localhost>;
$ FLUSH PRIVILEGES;
$ exit
```

in django
```bash
poetry add mysqlclient
```

postgres install
```bash
sudo dnf install postgresql-server
sudo dnf install postgresql-contrib
sudo postgresql-setup --initdb --unit postgresql
```

postgreSQL
```

```
