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
https://fedoraproject.org/wiki/PostgreSQL
https://stackpython.medium.com/how-to-start-django-project-with-a-database-postgresql-aaa1d74659d8
```bash
sudo dnf install postgresql-server
sudo dnf install postgresql-contrib
sudo postgresql-setup --initdb --unit postgresql
```

postgreSQL
```

```
