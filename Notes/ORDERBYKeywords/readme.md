# ORDER BY Keyword:

> The `ORDER BY` keyword is used to sort the result-set in ascending or descending order.The `ORDER BY` keyword sorts the records in ascending order by default.

SYNTAX:

```sql
ORDER BY column1, column2, ... ASC|DESC;
```

__For Example:__
```sql
SELECT * FROM Customers
ORDER BY Country;
```
> The following statement selects all customers from the "Customers" table, ordered by the "Country" in ascending order which is the default value.

```sql
SELECT * FROM Customers
ORDER BY Country DESC;
```
> The following statement selects all customers from the "Customers" table, ordered by the "Country" in descending order.
```sql
SELECT * FROM Customers
ORDER BY Country ASC,CustomerName DESC;
```
> The following statement selects all customers from the "Customers" table, ordered by Country in ascending order, but if some rows have the same Country, it orders them by CustomerName in descending order.