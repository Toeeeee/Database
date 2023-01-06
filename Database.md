**Connect to MySQL** 

```mysql -u root -p```

-u: user 

root: the MySQL username 

-p: password 

**View Database** 

```mysql> SHOW DATABASES;```

**Create Databases** 


```mysql> CREATE DATABASE IF NOT EXISTS database_name;```

**Select a Database** 

```mysql > USE database_name```

**Create a Table**

    mysql> CREATE TABLE IF NOT EXISTS tb2 (

        col1 INT,

        col2 VARCHAR(20),

        PRIMARY KEY (col1)
        );

**View Tables** 

```mysql> SHOW TABLES;```

**View Table Structure** 

```mysql> DESC tb1;```

**Insert Data**

    mysql> INSERT INTO tb1(col1, col2)
    VALUES (1, "value1"),
    (2, "value2");

**View Table Data** 

    mysql> SELECT * FROM tb1;

**Delete Data from Table** 

    mysql> DELETE FROM tb1 WHERE col1 = 1;

**Delete a Table** 

    mysql> DROP TABLE tb1;

**Delect a Database** 

    mysql> DROP DATABASE IF EXISTS db1;

----

[Nguồn tham khảo](https://linuxhint.com/mysql-commands-tutorial/)
