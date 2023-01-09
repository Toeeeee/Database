# Section 3: Filtering data 

### ```where```

1) Using MySQL WHERE clause with equality operator example

2) Using MySQL WHERE clause with the AND operator

3) Using MySQL WHERE clause with OR operator

4) Using MySQL WHERE clause with the BETWEEN operator


5) Using MySQL WHERE clause with the LIKE operator

6) Using MySQL WHERE clause with the IN operator

7) Using MySQL WHERE clause whit the IS NULL operator 

8) Using MySQL WHERE clause with comparison operators

    | Operator |
    |:--------:|
    |=|
    |<> or != |
    |<|
    |>|
    |<=|
    |>=|

### ```distinct```

Use the MySQL DISTINCT clause to remove duplicate rows from the result set returned by the SELECT clause.

    SELECT DISTINCT
        select_list
    FROM
        table_name
    WHERE 
        search_condition
    ORDER BY 
        sort_expression;


### ```and```


### ```or```

### ```in```

###  ```not in```

### ```between```

1) Using MySQL BETWEEN with numbers

2) Using MySQL BETWEEN operator with dates 



### ```like```


1) Using MySQL LIKE operator with the percentage (%) wildcard

2) Using MySQL LIKE operator with underscore ( _ ) wildcard 

3) Using MySQL NOT LIKE operator

    The backslash character (\) is the default escape character, if you don’t specify the escape character explicitly.

### ```limit``` 


The LIMIT clause is used in the SELECT statement to constrain the number of rows to return


    SELECT 
        select_list
    FROM
        table_name
    LIMIT [offset,] row_count;

In this syntax:

The ```offset``` specifies the offset of the first row to return. The offset of the first row is 0, not 1.

The ```row_count``` specifies the maximum number of rows to return.


The LIMIT and ORDER BY clauses

1) Using MySQL LIMIT to get the highest or lowest rows

2) Using MySQL LIMIT clause for pagination

    This query uses the ```COUNT(*)``` aggregate function to get the total rows from the table

3) Using MySQL LIMIT to get the nth highest or lowest value

       SELECT select_list
       FROM table_name
       ORDER BY sort_expression
       LIMIT n-1, 1;


MySQL LIMIT & DISTINCT clauses

