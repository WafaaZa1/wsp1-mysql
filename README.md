# wsp1-mysql
 
 kör igång ubunto
 kör
    sudo apt service mysql-restart
    sudo apt service apahce2 restart

sudo service mysql restart sudo service apache2 restart

Om apache2 bråkar pga. port 80. Starta services / tjänster i Windows. Stoppa branchcache och starta om apache2



    Setup
    Kör
  * sudo mysql -u root 
  
  För att gör ny användare
  * GRANT ALL PRIVILEGES ON *.* TO 'username'@'localhost' IDENTIFIED BY 'password';
  
  För att kolla vilka användare som finns

 * SELECT DISTINCT User FROM mysql.user;
 
 Start
 Kör

* mysql -u username -p

Port 80 fungerade inte för mig, då bytade jag den till port 88.
jag lyckas med att komma igång med PHP och sen kommenterade jag de sista raderna.


# SQL-Fråga.
alter table add/drop
select * from tablename
insert
describe TABLENAME;
update
create TABLENAME    column
use databcsename
show databasname
create index


