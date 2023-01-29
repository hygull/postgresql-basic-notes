# postgresql-basic-notes
A repository which contains notes for PostgreSQL database i.e. (source or web links of the articles etc.)

- PostgreSQL INNER JOIN Clause
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-inner-join/

- PostgreSQl LEFT JOIN Clause (LEFT OUTER JOIN Clause)
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-left-join/

- PostgreSQl RIGHT JOIN Clause (RIGHT OUTER JOIN Clause)
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-right-join/

- PostgreSQl Self-JOIN (An example of Inner / Left / Right)
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-self-join/

- PostgreSQL FULL OUTER JOIN (FULL JOIN) Clause 
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-full-outer-join/

- PostgreSQL CROSS JOIN Clause(Cartesian Product of rows in 2 or more tables, nxm)
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-cross-join/

- PostgreSQl NATURAL JOIN Clause

https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-natural-join/


---

# Examples

- CROSS JOIN Sql

```sql
SELECT *
FROM T1
INNER JOIN T2 ON true;
```

```sql
SELECT *
FROM T1
CROSS JOIN T2;
```

- NATURAL JOIN SQl 

```sql
SELECT	* FROM products
INNER JOIN categories USING (category_id);
```

The above statement is equivalent to

```sql
SELECT * FROM products
NATURAL JOIN categories;
```

```sql
SELECT * 
FROM city
NATURAL JOIN country;
```

