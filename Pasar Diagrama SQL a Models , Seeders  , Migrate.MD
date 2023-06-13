Aquí tienes un ejemplo de cómo crear una tabla de usuarios en SQL Server y un diagrama correspondiente:

```sql
-- Creación de la tabla "Usuarios"
CREATE TABLE Usuarios (
    ID INT PRIMARY KEY,
    Nombre VARCHAR(50),
    Apellido VARCHAR(50),
    CorreoElectronico VARCHAR(100),
    FechaRegistro DATE
);
```

El diagrama de la tabla "Usuarios" sería el siguiente:

```
+----+---------+----------+----------------------+---------------+
| ID | Nombre  | Apellido | CorreoElectronico    | FechaRegistro |
+----+---------+----------+----------------------+---------------+
|    |         |          |                      |               |
|    |         |          |                      |               |
|    |         |          |                      |               |
+----+---------+----------+----------------------+---------------+
```

Recuerda que este es solo un ejemplo básico y puedes ajustar los nombres de las columnas y sus tipos de datos según tus necesidades. Además, puedes agregar más columnas si es necesario para almacenar información adicional de los usuarios.