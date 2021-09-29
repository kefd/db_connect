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
