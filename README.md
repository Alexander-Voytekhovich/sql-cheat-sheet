SELECT  
&nbsp;&nbsp; COUNT  
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

- Select data with specific condition

valid condition operators:

```SQL
=
>
<
>=
<=
!= or <>
AND
OR
```

```SQL
SELECT column-1, сolumn-2 FROM table-name WHERE condition;
---
SELECT * FROM staff WHERE first_name = 'John' AND last_name = 'Doe';
SELECT * FROM staff WHERE experience > 1 AND experience <= 3;
```

- Get the number of fields 
```SQL
SELECT COUNT (сolumn-name) FROM table-name WHERE condition;
---
SELECT COUNT (name) FROM products WHERE discount > 10;
```

- Get the number of **unique** fields 
```SQL
SELECT COUNT (DISTINCT сolumn-name) FROM table-name WHERE condition;
---
SELECT COUNT (DISTINCT manufacturer) FROM products;
```
