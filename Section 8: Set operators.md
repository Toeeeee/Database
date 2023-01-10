

# Section 8: Set operators 


```union and union all```

        SELECT column_list
        UNION [DISTINCT | ALL]
        SELECT column_list
        UNION [DISTINCT | ALL]
        SELECT column_list
        ...

- MySQL ```union``` operator allows you to combine two of more results sets of queries into a single result set.


        SELECT id
        FROM t1
        UNION ALL
        SELECT id
        FROM t2;

