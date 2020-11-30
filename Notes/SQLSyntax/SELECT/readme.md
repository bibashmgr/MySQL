# SELECT Statement:

> `SELECT` statement is used to select data from a database. It returns all the data from the database,even tho they are same.

Syntax:
```sql
SELECT column1, column2, ...
FROM table_name;
```

> `SELECT DISTINCT` statement is used to return only distinct (different) values.

Syntax:
```sql
SELECT DISTINCT column1, column2, ...
FROM table_name;
```
> The `WHERE` clause is used to filter records.

Syntax:
```sql
SELECT column1, column2, ...
FROM table_name
WHERE condition;
```

### Operators in WHERE clause:
| Operators | Description                                      |
|---        |                                               ---|
| =	        | Equal	                                           |
| >	        | Greater than                                     |
| <	        | Less than	                                       |
| >=	    | Greater than or equal                            |
| <=	    | Less than or equal                               |
| <>	    | Not equal.                                       |
| BETWEEN	| Between a certain range	                       |
| LIKE	    | Search for a pattern	                           |
| IN	    | To specify multiple possible values for a column |

> The `WHERE` clause can be combined with AND, OR, and NOT operators.

- `AND` Syntax:
```sql
SELECT column1, column2, ...
FROM table_name
WHERE condition1 AND condition2 AND condition3 ...;
```
- `OR` Syntax:
```sql
SELECT column1, column2, ...
FROM table_name
WHERE condition1 OR condition2 OR condition3 ...;
```
- `NOT` Syntax:
```sql
SELECT column1, column2, ...
FROM table_name
WHERE NOT condition;
```

> The `ORDER BY` keyword is used to sort the result-set in ascending or descending order.

Syntax:
```sql
SELECT column1, column2, ...
FROM table_name
ORDER BY column1, column2, ... ASC|DESC;
```
