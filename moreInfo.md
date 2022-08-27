avant de faire un make server il faut deja construire le Makefile
pour ca : ~/rathena/configure Makefile.in

creation de l'utilisateur bdd : 
CREATE USER 'mydbuser01'@'localhost' IDENTIFIED BY 'passwdDB';
GRANT ALL PRIVILEGES ON mydbname.* TO 'myuser01'@'localhost';
