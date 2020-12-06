# INSERT INTO Statement:

The `INSERT INTO` statement is used to insert new records (i.e rows) in a table.

There are two ways to use `INSERT INTO` statement.They are:

1. The first way specifies both the column names and the values to be inserted:

```sql
INSERT INTO table_name (column1, column2, column3,.. ) VALUES (value1, value2, value3, ...);
```

2. If you are adding values for all the columns of the table, you do not need to specify the column names in the SQL query. However, make sure the order of the values is in the same order as the columns in the table.

```sql
INSERT INTO table_name VALUES (value1, value2, value3, ...);
```

