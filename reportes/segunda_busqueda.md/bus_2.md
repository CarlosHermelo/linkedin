# Recolección LinkedIn GenAI — CORRIDA 2 de 3

> **Importante.** Esta es una corrida autónoma. Recolectás 4 búsquedas, guardás tu propio archivo y terminás. No dependés de otras corridas. Si alguna búsqueda no da resultados, seguí con la siguiente — no abortes la corrida entera.

## Paso 0 — Verificación de sesión

1. Abrí `https://www.linkedin.com/feed/`.
2. Si ves login / CAPTCHA / muro público → detené y pedime que tome el control para loguearme. Reportá "SESIÓN NO ACTIVA".
3. Si ves tu feed con tu perfil → reportá "SESIÓN ACTIVA" y seguí.

---

## Búsquedas de esta corrida (términos planos, SIN operadores AND/OR/paréntesis)

Para cada una de estas 4 búsquedas:

1. `modelos de lenguaje`
2. `gobernanza IA`
3. `agente producción`
4. `costo IA tokens`

Procedimiento por búsqueda:

* tipo de resultado: **Publicaciones**;
* filtro de fecha: **Mes pasado**;
* **scroll obligatorio:** hacé scroll repetido hasta cargar al menos **20 publicaciones** o hasta que deje de cargar. NO te quedes con la primera pantalla;
* registrá las publicaciones según el formato de abajo.

> Meta de esta corrida: ~40-60 publicaciones únicas entre las 4 búsquedas.

---

## Clasificación obligatoria por tipo

Antes de registrar, clasificá cada publicación:

* **`opinion_o_caso`** — reflexión, experiencia, caso, pregunta abierta. Único tipo que mide interés temático.
* **`aviso_empleo`** — vacante. Se registra, se segrega.
* **`promocion`** — newsletter, curso, evento, producto sin contenido propio. Se registra, se segrega.
* **`duplicado`** — misma URL, o mismo autor+texto.

## Datos por publicación

* identificador consecutivo (esta corrida: 2xx → 201, 202, …);
* **tipo**;
* búsqueda de origen;
* fecha;
* autor;
* cargo;
* **seniority**: `directivo` (C-level/director/VP/head/founder/partner) · `mando_medio` (manager/lead/arquitecto sr) · `individual` (IC/analista/consultor solo/estudiante) · `organizacion` · `no_determinado`;
* **seguidores del autor** (si visible);
* empresa;
* ubicación;
* URL;
* texto completo o resumen fiel;
* reacciones / comentarios / republicaciones;
* **índice de interés** = `(reacciones + 2*comentarios + 3*republicaciones) / seguidores`, **solo si seguidores > 500**; si no, `no calculable`;
* preguntas de la publicación (**cadena literal, sin parafrasear**);
* preguntas de los comentarios (**literal**);
* necesidades/problemas (**cita literal**, no interpretación);
* rubro preliminar + evidencia;
* relación con Argentina (`confirmada` / `no confirmada` — NO es criterio de exclusión);
* observaciones.

## Deduplicación

Misma URL, o mismo autor+texto, o republicación sin cambios → marcar `duplicado`, no contar en totales.

---

## Salida

Guardá el archivo: `linkedin_genai_corrida2.md`

Encabezado:

```
# Relevamiento LinkedIn GenAI — Corrida 2 de 3
- Fecha de ejecución:
- Búsquedas: modelos de lenguaje, gobernanza IA, agente producción, costo IA tokens
- Estado de sesión:
- Publicaciones únicas: 
- opinion_o_caso: / aviso_empleo: / promocion: / duplicados:
- Con seguidores visibles (interés calculable):
```

Luego cada publicación con los campos de arriba.

## Reporte final (obligatorio)

Cerrá con: cuántas publicaciones cargó cada una de las 4 búsquedas tras scroll, si alguna dio 0 o pocas, si hubo algún muro o límite, y tiempo de ejecución. **No declares la tarea completa si trajiste pocas — reportá la falla.**

## Reglas de navegación

No likes, no comentarios, no republicar, no seguir, no mensajes, no formularios. Ante CAPTCHA/login/verificación → detené y pedí control.