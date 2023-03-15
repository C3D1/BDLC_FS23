# MySQL

```bash
sudo apt-get -y install mysql-server
```

The user root has no password:

```bash
sudo mysql -u root -p
Enter password: #just press enter
```

You should see a new sql prompt.

```text
Welcome to the MySQL monitor.  Commands end with ; or \g.
Your MySQL connection id is 8
Server version: 8.0.28-0ubuntu0.20.04.3 (Ubuntu)

Copyright (c) 2000, 2022, Oracle and/or its affiliates.

Oracle is a registered trademark of Oracle Corporation and/or its
affiliates. Other names may be trademarks of their respective
owners.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

mysql>
```

```sql
USE mysql;
UPDATE user SET plugin='mysql_native_password' WHERE User='root';
FLUSH PRIVILEGES;
exit;
```

Restart the mysql service:

```bash
sudo service mysql restart
```

### Create a Test_User in MySQL

We will create an own test_user in the `MySQL` database:

```bash
mysql -u root
```

```sql
CREATE USER 'test_user'@'localhost' IDENTIFIED BY 'test_user' password expire never;
GRANT ALL ON *.* TO 'test_user'@'localhost';
exit;
```

We can set the password of hive with the first login:

```bash
mysql -u test_user -ptest_user
```

<!--
Let's create a new database for the `hive_metastore`:

```sql
create database hive_metastore;
show databases;
exit;
``` -->

### Checking the Created Metastore - With the CLI

```bash
mysql -u hive -p
```

```sql
use hive_metastore;
show tables;
exit;
```

### Checking the Created Metastore - With `JupyterLab`

We can run SQL directly in `JupyterLab`. Open a terminal in `Jupyterlab` and install:

```bash
pip install SQLAlchemy==1.3.24
pip install pandas
pip install mysqlclient
pip install ipython-sql==0.4.1
```