# Mapa de Documentación — Navegación

> **Propósito**: Estructura completa de tabs, dropdowns y groups en docs.json.
>
> **Cuándo consultar**: Al modificar docs.json o agregar nuevas páginas.

---

## Estructura de Tabs

```
└── Tab: Documentación (16 páginas)
    ├── Dropdown: Módulo 1 — Fundamentos (3 págs)
    │   └── Group: Conceptos
    │       ├── conceptos-basicos
    │       ├── relaciones-er
    │       └── dbms-intro-sql
    │
    ├── Dropdown: Módulo 2 — SQL Básico (5 págs)
    │   ├── Group: Consultas
    │   │   ├── select-filtrado
    │   │   └── tipos-datos
    │   └── Group: Definición y manipulación
    │       ├── ddl
    │       ├── dml
    │       └── indices-vistas-sp
    │
    ├── Dropdown: Módulo 3 — Consultas Intermedias (5 págs)
    │   ├── Group: Filtrado y agrupación
    │   │   ├── patrones-rangos
    │   │   └── ordenamiento-agrupacion
    │   ├── Group: Funciones y subconsultas
    │   │   ├── funciones
    │   │   └── subconsultas
    │   └── Group: Práctica
    │       └── examen
    │
    ├── Dropdown: Módulo 4 — JOINs (3 págs)
    │   ├── Group: Combinación de tablas
    │   │   ├── tipos-join
    │   │   └── join-multitabla-union
    │   └── Group: Práctica
    │       └── examen
    │
    └── Dropdown: Módulo 5 — SQL Avanzado (3 págs)
        ├── Group: Temas avanzados
        │   ├── consultas-avanzadas
        │   └── seguridad-herramientas
        └── Group: Práctica
            └── examen
```

---

## Reglas de navegación

1. **Dentro de un tab**, `groups` y `dropdowns` NO pueden convivir
2. Si un tab tiene `dropdowns`, los `groups` se ignoran
3. Páginas globales (como "Inicio") van en `navigation.global.anchors`
4. **Nunca listas planas >5 páginas** — usar nested groups
5. **Sub-grupos de 2-4 páginas** cada uno
