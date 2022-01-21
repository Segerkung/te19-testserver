# Anteckningar

SQL kod

 "sudo service mysql restart" varje gång

 mysql -u Leo -p

 sudo mysql -u root

 mysql> CREATE USER 'Leo'@'localhost' IDENTIFIED BY 'Mitt lösenord';
 GRANT ALL PRIVILEGES ON *.* TO 'Leo'@'localhost';

 select * from tasks

"update tasks set completed=true, updated_at=now() where id=1;" uppdatera en to do från false till true.

