## Los primeros 10 registros de una consulta

```sql
SELECT *
FROM (
  SELECT *
  FROM esquema.table_1
  ORDER BY id DESC
)
WHERE ROWNUM <= 10
```
