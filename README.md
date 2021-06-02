SELECT  
&nbsp;&nbsp; DISTINCT  
&nbsp;&nbsp;&nbsp;&nbsp; FROM  
&nbsp;&nbsp;&nbsp;&nbsp; WHERE  
&nbsp;&nbsp; GROUP BY  
&nbsp;&nbsp; HAVING  
&nbsp;&nbsp;&nbsp;&nbsp; ORDER BY  
&nbsp;&nbsp;&nbsp;&nbsp; ASC | DESC  
&nbsp;&nbsp; LIMIT  

- Select all values from the table.

```SQL
SELECT * FROM table-name;
```
- Select `сolumn-1`, `column-2` from the table

```SQL
SELECT сolumn-1, сolumn-2 FROM table-name;
```

- Select **unique** values from the table and `column-2`

```SQL
SELECT DISTINCT сolumn-2 FROM table-name;
```
