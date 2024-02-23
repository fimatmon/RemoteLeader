# RemoteLeader
RemoteLeader is a remote work management application. 

This is a presentation version of it.

Username : Admin
Password: 1234Admin

Version 1.51 has an English GUI

MariaDB user creation example:

A new user:
CREATE USER 'valvoja'@localhost IDENTIFIED BY 'mariadb';

Grant rights to use the database by the user valvoja:
GRANT ALL PRIVILEGES ON *.* TO 'valvoja'@localhost IDENTIFIED BY 'mariadb';
