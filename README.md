# brana-ql
A high level query lenguaje proposal

## Example

Get latest 12 activities in ascending order, where expiration_date is greater than today and author id is equal to 15
```
  activity by {latest 12, order asc} where {expiration_date > today, author = 15}
```

or 

```
  activity/latest/12/asc {expiration_date > today, author = 15}
```
