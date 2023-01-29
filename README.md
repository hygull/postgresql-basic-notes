# postgresql-basic-notes
A repository which contains notes for PostgreSQL database i.e. (source or web links of the articles etc.)

- PostgreSQL INNER JOIN Clause
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-inner-join/

- PostgreSQL LEFT JOIN Clause (LEFT OUTER JOIN Clause)
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-left-join/

- PostgreSQL RIGHT JOIN Clause (RIGHT OUTER JOIN Clause)
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-right-join/

- PostgreSQL Self-JOIN (An example of INNER / LEFT / RIGHT)
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-self-join/

- PostgreSQL FULL OUTER JOIN (FULL JOIN) Clause 
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-full-outer-join/

- PostgreSQL CROSS JOIN Clause(Cartesian Product of rows in 2 or more tables, nxm)
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-cross-join/

- PostgreSQL NATURAL JOIN Clause
https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-natural-join/


---

# Examples

- CROSS JOIN SQL

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

- NATURAL JOIN SQL

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

Thanks in advance.