# Section 4: Joining tables

MySQL supports the following types of joins:

1. Inner join
2. Left join
3. Right join
4. Cross join

## ```Inner Join ```

    SELECT 
        select_list
    FROM 
        t1
    INNER JOIN t2 ON join_condition;

![m](https://github.com/Toeeeee/Database/blob/main/Images/Screenshot%20from%202023-01-09%2011-44-41.png?raw=true)


The joined columns of both tables have the same name, you can use the ```USING``` syntax

Ex: 

![m](https://github.com/Toeeeee/MySQL/blob/main/Images/Screenshot%20from%202023-01-09%2015-07-00.png?raw=true)

    SELECT 
        productCode, 
        productName, 
        textDescription
    FROM
        products
    INNER JOIN productlines USING (productline);
