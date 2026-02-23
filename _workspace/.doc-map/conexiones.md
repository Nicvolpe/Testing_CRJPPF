# Mapa de Documentación — Conexiones

> **Propósito**: Cross-references entre archivos de documentación.
>
> **Cuándo consultar**: Al decidir qué enlaces agregar entre páginas.

---

## Conexiones por módulo

### Módulo 1 → Módulo 2

| Desde | Hacia | Motivo |
|-------|-------|--------|
| dbms-intro-sql | select-filtrado | Profundización en SELECT |
| relaciones-er | ddl | Crear relaciones con CREATE TABLE y FK |

### Módulo 2 → Módulo 3

| Desde | Hacia | Motivo |
|-------|-------|--------|
| select-filtrado | patrones-rangos | Filtrado avanzado con LIKE, BETWEEN, IN |
| dml | indices-vistas-sp | Objetos que complementan la manipulación |

### Módulo 2 → Módulo 5

| Desde | Hacia | Motivo |
|-------|-------|--------|
| indices-vistas-sp | seguridad-herramientas | Procedimientos almacenados previenen inyección SQL |

### Módulo 3 → Módulo 4

| Desde | Hacia | Motivo |
|-------|-------|--------|
| subconsultas | tipos-join | JOINs como alternativa a subconsultas |
| ordenamiento-agrupacion | consultas-avanzadas | CASE + GROUP BY avanzado |

### Módulo 4 → Módulo 5

| Desde | Hacia | Motivo |
|-------|-------|--------|
| join-multitabla-union | consultas-avanzadas | Consultas complejas combinando todo |

---

## Reglas de cross-reference

### Cuándo agregar

1. **Complemento directo**: La otra página completa la información
2. **Prerrequisito**: Se necesita leer primero la otra página
3. **Profundización**: Para quien quiera más detalle

### Cuándo NO agregar

1. **Forzado**: No hay relación real
2. **Repetido**: Ya existe la referencia en la misma página
3. **Obvio**: La navegación ya lo conecta (mismo dropdown)

### Formato

```mdx
<Tip>
Para más detalle, consultá [Título página](/ruta/pagina).
</Tip>
```
