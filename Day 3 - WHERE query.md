# WHERE query

**WHERE** keyword is used for fetching filtered data in a result set (final table which we get after executing ```SELECT * FROM table_name``` query)

  - It is used to fetch data according to a particular criteria.
  - WHERE keyword can also be used to filter data by matching patterns.

### Basic Syntax:

```sh
SELECT column1, column2 FROM table_name WHERE column_name operator value;

column1 , column2: fields in the table
table_name: name of table
column_name: name of field used for filtering the data
operator: operation to be considered for filtering
value: exact value or pattern to get related data in result set
```

### What operators can we use with WHERE query ?

| Operator | Description |
|:--------:|:-----------:|
| >  | Greater than |
| >= | Greater than or equal to |
| <  | Less than |
| <= | Less than or equal to|
| == | Equal to |
| <> | Not equal to|
| BETWEEN | In an inclusive range|
| LIKE | Search for a pattern |
| IN | To specify multiple possible values for a column |

