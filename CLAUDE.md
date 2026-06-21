# LinkedIn Positioning — CLAUDE.md

> ⚠️ **INSTRUCCIÓN PARA AGENTES**: Antes de cualquier tarea, leer y cargar el contenido completo de `AGENTS.md`. Toda la inteligencia operativa del sistema (agentes, roles, flujos, prompts) está definida allí.

## Propósito de esta carpeta

Gestión integral del posicionamiento profesional de **Carlos Hermelo** en LinkedIn, enfocado en inteligencia artificial generativa.

---

## Posicionamiento

> **"Profesional especializado en inteligencia artificial generativa, enfocado en identificar oportunidades, construir soluciones y aplicar esta tecnología en procesos, productos y organizaciones."**

---

## Estrategia

Usar LinkedIn para:
1. **Ganar visibilidad** en inteligencia artificial generativa
2. **Relacionarse** con profesionales de tecnología para generar sinergias
3. **Conectar con decisores de negocio** que puedan necesitar soluciones basadas en IA generativa

### Audiencias objetivo

| Audiencia | Por qué importa |
|---|---|
| Profesionales de tecnología | Sinergias, colaboraciones, referidos |
| Decisores de negocio (C-level, directores) | Clientes potenciales, proyectos |
| Comunidad IA/GenAI | Credibilidad, visibilidad temática |

---

## Estructura de la carpeta

```
linkedin/
├── CLAUDE.md           # Este archivo — contexto global del proyecto
├── AGENTS.md           # Definición de agentes y flujos de trabajo
├── contenido/          # Posts, artículos, comentarios redactados
│   ├── borradores/
│   └── publicado/
├── estrategia/         # Análisis, planes, decisiones estratégicas
├── reportes/           # Reportes generados por agentes (métricas, análisis)
└── skills/             # Skills personalizadas para este proyecto
```

---

## Convenciones para agentes

- **Idioma de trabajo**: Español (posts pueden ser español o inglés según audiencia)
- **Tono**: Experto pero accesible, sin jerga innecesaria
- **Formato de reportes**: Markdown en `/reportes/` con fecha `YYYY-MM-DD_nombre.md`
- **Formato de contenido**: Markdown en `/contenido/` con tipo y fecha
- **Verificación**: Usar la skill `verificador-datos` antes de publicar contenido con afirmaciones factuales

---

## Pilares de contenido

1. **Educación en GenAI** — conceptos, casos de uso, herramientas
2. **Aplicaciones prácticas** — cómo implementar IA en procesos reales
3. **Tendencias y oportunidades** — hacia dónde va la tecnología
4. **Casos y resultados** — proyectos propios, aprendizajes concretos

---

## Skills disponibles

| Skill | Trigger | Uso |
|---|---|---|
| `verificador-datos` | Automático en contenido | Fact-check antes de publicar |
| `ng-prompt-mejorador` | `ttt` al final del mensaje | Mejorar prompts con metodología Andrew Ng |
| `skkp` | `skkp` al final del mensaje | Mejora rápida de prompts |
| `xkk` | `xkk` al final del mensaje | Otra variante de mejora de prompts |
| `pptx` | Mencionar "presentación" | Presentaciones para eventos o clientes |
| `docx` | Mencionar "Word doc" | Propuestas, estrategias |
| `xlsx` | Mencionar "Excel/spreadsheet" | Seguimiento de métricas y KPIs |
| `pdf` | Mencionar ".pdf" | Generar o procesar PDFs |

---

## KPIs de seguimiento

- Seguidores (crecimiento mensual)
- Impresiones por post
- Tasa de engagement (reacciones + comentarios / impresiones)
- Nuevas conexiones estratégicas por mes
- Solicitudes de contacto inbound de decisores

---

## Notas operativas

- Reportes → `/reportes/YYYY-MM-DD_nombre.md`
- Contenido aprobado → `/contenido/publicado/`
- Borradores → `/contenido/borradores/`
- Revisar estrategia cada 4 semanas según métricas
