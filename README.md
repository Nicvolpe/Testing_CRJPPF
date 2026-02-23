# Mintlify Documentation Template

Template reutilizable para proyectos de documentación técnica con **Mintlify + Claude Code**.

---

## Uso rápido

```bash
# 1. Clonar el template
git clone https://github.com/[TU_USUARIO]/mintlify-doc-template.git mi-documentacion
cd mi-documentacion

# 2. Buscar y reemplazar placeholders globales
# Reemplazar [NOMBRE_PROYECTO] y [DESCRIPCION_PROYECTO] en todo el proyecto

# 3. Personalizar docs.json (name, description, colors)

# 4. Completar secciones [COMPLETAR: ...] en CLAUDE.md

# 5. Ejecutar
npx mintlify dev
```

---

## Estructura

```
mintlify-doc-template/
├── app/                                  # Contenido publicable
│   ├── documentacion/                    # Tab Documentación
│   │   └── empezar/
│   │       ├── introduction.mdx          # Getting started
│   │       └── ejemplo-seccion/
│   │           ├── introduccion.mdx      # Ejemplo de intro de sección
│   │           └── ejemplo-pagina.mdx    # Showcase de TODOS los componentes
│   └── procesos/
│       └── introduction.mdx              # Tab Procesos (ejemplo simple)
├── _workspace/                           # Archivos internos (NO se publican)
│   └── .doc-map/                         # Sistema de mapa de documentación
│       ├── _index.md                     # Punto de entrada (leer primero)
│       ├── navegacion.md                 # Estructura de docs.json
│       ├── documentacion.md              # Índice Tab Documentación
│       ├── procesos.md                   # Índice Tab Procesos
│       ├── conexiones.md                 # Cross-references
│       └── conceptos.md                  # Conceptos compartidos
├── logo/
│   ├── light.svg                         # Logo modo claro
│   └── dark.svg                          # Logo modo oscuro
├── docs.json                             # Configuración Mintlify + navegación
├── introduction.mdx                      # Home page
├── CLAUDE.md                             # Instrucciones para Claude Code
├── README.md                             # Este archivo
└── .gitignore
```

---

## Qué incluye

| Componente | Descripción |
|------------|-------------|
| **CLAUDE.md** | Instrucciones completas para Claude Code con estándares de calidad, reglas de navegación, formato MDX y sistema de doc-map |
| **docs.json** | Navegación skeleton demostrando Tab → Dropdown → Group → Nested Group → Page |
| **introduction.mdx** | Home page con stack, glosario, camino de aprendizaje y métricas |
| **Páginas de ejemplo** | 4 páginas que demuestran todos los componentes Mintlify disponibles |
| **`_workspace/.doc-map/`** | Sistema de 6 archivos para mantener coherencia en proyectos grandes |
| **logo/** | SVGs placeholder para modo claro/oscuro |

---

## Estándares de calidad incluidos

- **Perfiles de audiencia**: Junior que aprende, Senior que consulta
- **Tabla de profundidad obligatoria**: QUÉ/POR QUÉ/CÓMO/DÓNDE
- **Reglas de navegación**: Segmentación, nested groups, iconos por capa
- **Formato MDX**: Frontmatter obligatorio (title + description 120-160 chars)
- **Diagramas Mermaid**: Obligatorios (nunca ASCII art), máximo ~12 nodos
- **Cross-references**: Criterios claros de cuándo agregar y cuándo no

---

## Requisitos

- **Node.js** 20+ (recomendado via nvm)
- `npx mintlify dev` para desarrollo local

---

## Personalización

Ver la sección **"Cómo usar este template"** al inicio de `CLAUDE.md` para la guía completa con checklist.

---

## Referencias

- [Mintlify Docs](https://mintlify.com/docs)
- [Componentes Mintlify](https://mintlify.com/docs/components)
- [Mermaid Diagrams](https://mermaid.js.org)
