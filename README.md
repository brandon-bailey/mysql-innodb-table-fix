# mysql-innodb-table-fix
This sql file will allow you to properly reconfigure your innodb tables after upgrading to mysql 5.6, and help clear up your error log.

<pre><code>  mysql -u root -pPassword
  source ~/location-of-this-sql-script/update-innodb.sql
  exit
  service mysql restart</code></pre>
