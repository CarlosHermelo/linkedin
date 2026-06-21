# Recolección de publicaciones de LinkedIn sobre IA en Argentina

## Rol

Actuá como recolector y normalizador de publicaciones públicas de LinkedIn.

Tu tarea es buscar publicaciones recientes sobre inteligencia artificial, registrar los datos encontrados y entregar el resultado en un archivo Markdown.

No realices todavía un análisis general, un ranking de temas ni conclusiones.

---

## Objetivo

Recolectar publicaciones de LinkedIn sobre inteligencia artificial correspondientes a los últimos 30 días.

La búsqueda no debe limitarse a un rubro determinado.

El rubro o sector económico deberá registrarse como un atributo de cada publicación para permitir un análisis posterior por sectores como:

* Finanzas
* Salud
* Educación
* Industria
* Comercio y retail
* Administración pública
* Tecnología
* Agro
* Logística
* Construcción
* Servicios profesionales
* Otros

Priorizar publicaciones relacionadas con Argentina.

---

## Búsquedas

Realizá búsquedas separadas en LinkedIn con estos términos:

1. `"inteligencia artificial"`
2. `"IA generativa"`
3. `GenAI`
4. `ChatGPT`
5. `Copilot`
6. `"agentes de IA"`
7. `"automatización con IA"`
8. `"modelos de lenguaje" OR LLM`

En cada búsqueda:

* seleccionar el tipo de resultado `Publicaciones`;
* aplicar el filtro de fecha `Último mes`;
* recorrer los resultados disponibles;
* evitar utilizar solamente el feed de inicio;
* recolectar hasta alcanzar aproximadamente 120 publicaciones únicas entre todas las búsquedas.

No es necesario alcanzar exactamente esa cantidad si LinkedIn no presenta suficientes publicaciones relevantes.

---

## Criterios de inclusión

Incluir una publicación cuando:

* trata principalmente sobre inteligencia artificial;
* describe una herramienta, problema, experiencia, pregunta, aplicación o caso de uso;
* fue publicada durante los últimos 30 días;
* tiene relación con Argentina porque el autor, la empresa, el caso o el mercado mencionado es argentino.

Cuando la relación con Argentina no pueda comprobarse, indicarlo como:

`Relación con Argentina: no confirmada`

---

## Datos que se deben registrar

Por cada publicación recopilar:

* identificador consecutivo;
* búsqueda mediante la cual fue encontrada;
* fecha;
* autor;
* cargo del autor, cuando sea visible;
* empresa u organización;
* ubicación, cuando sea visible;
* URL;
* texto completo de la publicación o resumen fiel;
* cantidad de reacciones;
* cantidad de comentarios;
* cantidad de republicaciones, cuando sea visible;
* preguntas formuladas en la publicación;
* preguntas encontradas en comentarios visibles;
* comentarios que expresen problemas, necesidades o interés;
* rubro preliminar;
* evidencia utilizada para determinar el rubro;
* relación con Argentina;
* observaciones.

El rubro debe inferirse principalmente por:

1. actividad de la empresa;
2. cargo y perfil profesional del autor;
3. organización mencionada;
4. caso de uso presentado;
5. problema sectorial tratado.

Cuando no sea posible determinarlo, usar:

`Rubro preliminar: no determinado`

No clasificar todavía el tema específico de IA.

---

## Eliminación de duplicados

Considerar duplicadas las publicaciones que tengan:

* la misma URL;
* el mismo autor y texto;
* el mismo contenido republicado sin modificaciones relevantes.

Conservar una sola versión y registrar mediante qué búsquedas fue encontrada.

---

## Formato del archivo

Crear el archivo:

`linkedin_ia_argentina_ultimos_30_dias.md`

Utilizar esta estructura:

# Relevamiento de LinkedIn — Inteligencia artificial en Argentina

## Datos del relevamiento

* Fecha de ejecución:
* Período analizado:
* Cantidad de búsquedas:
* Cantidad de publicaciones únicas:
* Cantidad con relación confirmada con Argentina:
* Cantidad con relación no confirmada:

---

## Publicación 001

* **Búsqueda de origen:**
* **Fecha:**
* **Autor:**
* **Cargo:**
* **Empresa u organización:**
* **Ubicación:**
* **URL:**
* **Reacciones:**
* **Comentarios:**
* **Republicaciones:**
* **Rubro preliminar:**
* **Evidencia del rubro:**
* **Relación con Argentina:**

### Contenido

Texto completo o resumen fiel.

### Preguntas de la publicación

* Pregunta encontrada.
* Sin preguntas explícitas.

### Preguntas de los comentarios

* Pregunta encontrada.
* Sin preguntas visibles.

### Necesidades o problemas expresados

* Necesidad o problema identificado.
* No identificado.

### Comentarios relevantes

* Comentario relevante.
* Sin comentarios relevantes visibles.

### Observaciones

Información adicional necesaria para interpretar el registro.

---

## Reglas de navegación

* No dar “Me gusta”.
* No comentar.
* No republicar.
* No seguir personas.
* No enviar invitaciones.
* No enviar mensajes.
* No modificar ninguna configuración.
* No completar formularios.
* No interactuar con publicaciones.

Si aparece CAPTCHA, contraseña, código de seguridad, verificación de identidad o autorización sensible:

1. detener la navegación;
2. no intentar resolverlo;
3. solicitar que el usuario tome el control;
4. continuar solamente cuando el usuario devuelva el control.

---

## Resultado

Entregar únicamente el archivo Markdown con los registros recolectados.

No generar todavía:

* ranking de temas;
* agrupación temática;
* conclusiones;
* recomendaciones editoriales;
* ideas para publicaciones;
* análisis estratégico.
