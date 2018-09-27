# MySQL JSON handle functions
Extend your MySQL 5.x version for using JSON in simple textfields with SELECT and UPDATE, without any plugin or crappy code.

You can simply add the following functions to your MySQL Database and use them in your regular SQL-Queries.

We use those functions in since one year in production with several customers and on very high loaded databases. And we had no issues with them recently.

Currently you can only use one-directional json arrays, such as:
```json


```

# the functions

## json_get

Returns the value of a json-item in a textfield.

### Params:

- *db_field:* the database column inn a table, which contains a json item
- *json_field:* the name of the json-subitem in the json-object

### Example:

*Query:* 
```SQL

```
*Result:*
```

```


## json_set 


## json_get_array_count


## json_get_array_list

Returns a list of the values in a json array.

### Params:

- *db_field:* the database column inn a table, which contains a json item
- *json_field:* the name of the json-subitem in the json-object

### Example:

*Query:* 
```SQL

```
*Result:*
```

```


## json_get_array
