# WHERE Clause:
> The `WHERE` clause is used to filter records.

Syntax:
```sql
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
WHERE condition1 AND condition2 AND condition3 ...;
```
- `OR` Syntax:
```sql
WHERE condition1 OR condition2 OR condition3 ...;
```
- `NOT` Syntax:
```sq
WHERE NOT condition;
```

> `WHERE` clause use  `IS NULL` and `IS NOT NULL` operators instead of comparison operator `<>`.

```sql
WHERE column_name IS NULL;
```

```sql
WHERE column_name IS NOT NULL;
```

