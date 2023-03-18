


### Practica 1

- Primero actualizar el archivo
    ```bash
    liquibase update-sql
    ```
- Crear una nueva tabla en el archivo changelog
- Generar la tabla
    ```bash 
    liquibase update
    ```
- Ir al propierties  a bd origen y cambiar el Dev a INTEGRATION
- Ejecutar la creacion de una tabla difertente a la otra
    ```bash 
    liquibase update
    ```