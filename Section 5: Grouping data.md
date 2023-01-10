# Section 5: Grouping data 


```group by```

- The GROUP BY statement groups rows that have the same values into summary rows.

- Using the clause ```GROUP BY``` with aggregate functions sush as SUM(), AVG(), MAX(), MIN(), COUNT().

        SELECT 
            c1, c2,..., cn, aggregate_function(ci)
        FROM
            table
        WHERE
            where_conditions
        GROUP BY c1 , c2,...,cn;

```having```

- The HAVING clause is used in the SELECT statement to specify filter conditions for a group of rows or aggregates.

- The HAVING clause is often used with the GROUP BY clause to filter groups based on a specified condition. If you omit the GROUP BY clause, the HAVING clause behaves like the WHERE clause.

        SELECT 
            select_list
        FROM 
            table_name
        WHERE 
            search_condition
        GROUP BY 
            group_by_expression
        HAVING 
            group_condition;


```rollup```

