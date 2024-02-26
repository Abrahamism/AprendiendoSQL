# Iniciando en SQL
*Se colocaran las pequeñas cosas que vaya aprendiendo;*


**-Cambiar el nombre a una VW o Table:**
```sql
ALTER VIEW nombre_viejo RENAME TO nombre_nuevo;
```
**-Crear una VW o Table:**
```sql
CREATE OR REPLACE VIEW SCHEMA.VW_NOMBRE_DE_LA_VW AS (
);
```
**-Para convertir los resultados de una columna a mayúsculas en SQL**
```sql
UPPER(customers)
```
**-Ver las VW o Tables de los Schemas**
```sql
SHOW VIEWS IN SCHEMA EMPRESA_MX
```
**-La función EXPLAIN te permite ver el plan de ejecución de una consulta SQL**
```sql
EXPLAIN ANALYZE SELECT * FROM customers WHERE country = 'Mexico';
```
