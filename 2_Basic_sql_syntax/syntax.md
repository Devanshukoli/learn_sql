# Basic SQL Syntax

- `SELECT` statement is for fetching data from the database.

```SQL
SELECT col1, col2 FROM table_name;
```

- `SELECT * FROM table_name` : Here, `*` (star) selecter will select everything form that table.

* `INSERT INTO` is for inserting value into the database.

```SQL
INSERT INTO table_name (col1, col2, ...)
VALUES (val1, val2, ...)
```

- `UPDATE` is for modifing existing records of the database.

```SQL
UPDATE table_name
SET col1 = val1, col2 = val2, ....
WHERE condition;
```

- `DELETE` is for remove rows from table.

```SQL
DELETE FROM table_name WHERE condition;
```

- `CREATE TABLE` is for creating new table in the database.

```SQL
CREATE TABLE table_name (
  col1 dataType constraints,
  col2 dataType constraints,
  ...
);
```

- `ALTER TABLE` is for _adding_, _deleting_ or _modifing_ columns in the existing table.

```SQL
-- To add a column
ALTER TABLE table_name
ADD column_name datatype;

-- To delete/drop column
ALTER TABLE table_name
DROP COLUMN column_name;

-- To modify existing column
ALTER TABLE table_name
MODIFY COLUMN column_name datatype;
```

- `DROP TABLE` is for droping existing table in database.

```SQL
DROP TABLE table_name;
```

- `CREATE DATABASE` is for creating databse.

```SQL
CREATE DATABASE mydatabase;
```

- **NOTE** : _SQL_ is not case sensitivie.

- There is also `ORDER BY` AND `DESC` or `ASC` keywords used for sorting out records in the manner you desire. 😃
