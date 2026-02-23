# Mapa de Documentación — Conceptos Compartidos

> **Propósito**: Conceptos que aparecen en múltiples archivos y deben mantenerse coherentes.
>
> **Cuándo consultar**: Al modificar conceptos que cruzan secciones.

---

## Conceptos técnicos clave

### Claves primarias y foráneas (PK/FK)

| Concepto | Archivos donde aparece |
|----------|------------------------|
| Primary Key (PK) | conceptos-basicos, relaciones-er, ddl, tipos-join |
| Foreign Key (FK) | relaciones-er, ddl, tipos-join, join-multitabla-union |
| Integridad referencial | relaciones-er, tipos-join, join-multitabla-union |

**Al modificar**: Verificar que la definición sea consistente en todos los archivos. PK = identificador único, no nulo, no repetible. FK = referencia a PK de otra tabla.

### Tipos de JOIN

| Concepto | Archivos donde aparece |
|----------|------------------------|
| INNER JOIN | tipos-join, join-multitabla-union, examen-4, consultas-avanzadas |
| LEFT JOIN | tipos-join, join-multitabla-union, consultas-avanzadas |
| RIGHT JOIN | tipos-join |
| FULL OUTER JOIN | tipos-join |

**Al modificar**: Mantener consistente la explicación de qué filas se incluyen/excluyen en cada tipo.

### DDL y DML

| Concepto | Archivos donde aparece |
|----------|------------------------|
| DDL (CREATE, ALTER, DROP) | dbms-intro-sql, ddl |
| DML (INSERT, UPDATE, DELETE) | dbms-intro-sql, dml |
| SELECT | select-filtrado, patrones-rangos, ordenamiento-agrupacion, funciones, subconsultas |

**Regla**: DDL define estructura, DML manipula datos. SELECT es parte de DML pero se trata por separado por su complejidad.

### Subconsultas

| Concepto | Archivos donde aparece |
|----------|------------------------|
| Subconsulta en WHERE | subconsultas, examen-3, examen-4 |
| Subconsulta en columna | subconsultas |
| Subconsulta como tabla origen | subconsultas, consultas-avanzadas, examen-5 |

**Al modificar**: Siempre recordar que las subconsultas como tabla origen requieren alias obligatorio.

---

## Glosario institucional

| Término | Significado |
|---------|-------------|
| BDD | Base de datos |
| RDBM | Sistema de gestión de bases de datos relacional |
| DBMS | Database Management System |
| DDL | Data Definition Language (CREATE, ALTER, DROP) |
| DML | Data Manipulation Language (INSERT, UPDATE, DELETE, SELECT) |
| PK | Primary Key — Clave primaria |
| FK | Foreign Key — Clave foránea |
| JOIN | Operación que combina filas de dos o más tablas |
| Tupla | Fila o registro de una tabla |
| Collation | Reglas de comparación de cadenas de texto |
