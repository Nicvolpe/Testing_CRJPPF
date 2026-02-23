# Mapa de Documentación — Tab Documentación

> **Propósito**: Índice detallado del Tab Documentación con conceptos clave por sección.
>
> **Cuándo consultar**: Al trabajar en cualquier página del Tab Documentación.

---

## Dropdown: Módulo 1 — Fundamentos

### Group: Conceptos

| Página | Conceptos clave |
|--------|-----------------|
| conceptos-basicos | Datos vs información, modelos de BDD, tablas, campos, registros, tuplas |
| relaciones-er | PK, FK, relaciones 1:1/1:N/N:M, tabla puente, diagramas ER |
| dbms-intro-sql | DBMS, crear/mantener/analizar/manipular, DDL, DML, primeros comandos |

---

## Dropdown: Módulo 2 — SQL Básico

### Group: Consultas

| Página | Conceptos clave |
|--------|-----------------|
| select-filtrado | SELECT, WHERE, operadores, AND/OR/NOT, LIMIT, DISTINCT, COUNT |
| tipos-datos | INT, VARCHAR, TEXT, DATE, BLOB, charset, collation, ASCII, Unicode |

### Group: Definición y manipulación

| Página | Conceptos clave |
|--------|-----------------|
| ddl | CREATE TABLE, restricciones (NOT NULL, UNIQUE, PK, FK, DEFAULT, CHECK), ALTER, DROP |
| dml | INSERT INTO, UPDATE, DELETE, IS NULL, IS NOT NULL |
| indices-vistas-sp | Índices, vistas (CREATE VIEW), procedimientos almacenados, parámetros |

---

## Dropdown: Módulo 3 — Consultas Intermedias

### Group: Filtrado y agrupación

| Página | Conceptos clave |
|--------|-----------------|
| patrones-rangos | LIKE, comodines (%, _, []), BETWEEN, IN |
| ordenamiento-agrupacion | ORDER BY, ASC/DESC, GROUP BY, HAVING, SELECT CASE |

### Group: Funciones y subconsultas

| Página | Conceptos clave |
|--------|-----------------|
| funciones | SUM, MIN, MAX, AVG, ROUND, LENGTH, UPPER, LOWER, YEAR, MONTH, DATEDIFF |
| subconsultas | Subconsultas en WHERE, en columna, como tabla origen, alias obligatorio |

### Group: Práctica

| Página | Conceptos clave |
|--------|-----------------|
| examen | 5 ejercicios resueltos: LIKE, IN, BETWEEN, COUNT+GROUP BY, CASE |

---

## Dropdown: Módulo 4 — JOINs

### Group: Combinación de tablas

| Página | Conceptos clave |
|--------|-----------------|
| tipos-join | JOIN implícito, INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN |
| join-multitabla-union | JOINs encadenados (3+ tablas), UNION, UNION ALL, requisitos |

### Group: Práctica

| Página | Conceptos clave |
|--------|-----------------|
| examen | 5 ejercicios resueltos: ventas por producto, cliente, suministrador, categoría, ciudad |

---

## Dropdown: Módulo 5 — SQL Avanzado

### Group: Temas avanzados

| Página | Conceptos clave |
|--------|-----------------|
| consultas-avanzadas | Subconsultas como origen con JOINs, totales por orden, CASE+GROUP BY, análisis temporal |
| seguridad-herramientas | Inyección SQL, prevención, HeidiSQL, phpMyAdmin, librerías PHP/Python |

### Group: Práctica

| Página | Conceptos clave |
|--------|-----------------|
| examen | 5 ejercicios resueltos: ventas multi-cliente, CASE+suministrador, período+empleado, transportista, mayor orden por ciudad |
