# UD1 A1. Lenguajes de marcas

### 1. Indica qué es un lenguaje de marcas
> Un lenguaje de marcado o lenguaje de marcas es una forma de codificar un documento que, junto con el texto, incorpora etiquetas o marcas que contienen información adicional acerca de la estructura del texto o su presentación.

### 2. Características generales de los lenguajes de marcas.
> **Texto Plano:**
> Los archivos son de texto plano, facilitando su edición con cualquier editor de texto y su independencia del sistema operativo.
>
> **Compactibilidad:**
> Las etiquetas de marcado se mezclan con el contenido, definiendo su formato y estructura, como `<h2>Contenido</h2>`.
>
> **Independencia del Dispositivo Final:**
> Los documentos pueden ser interpretados de manera distinta según el dispositivo, como móviles, ordenadores o impresoras.
>
> **Especialización:**
> Se usan en diferentes áreas: gráficos vectoriales (SVG), sindicación de contenidos (RSS), notación científica (MathML), y más.
>
> **Flexibilidad:**
> Se integran con otros lenguajes, como PHP o JavaScript, y permiten combinar varios lenguajes en un solo archivo, como XHTML y SVG.

### 3. Clasifica los lenguajes de marcas e identifica los más relevantes.
> **De presentación:**
> Definen la apariencia visual del texto (tamaño, fuente, negrita) sin preocuparse por su estructura. Se usan en procesadores de texto. Ejemplos: RTF y TeX.
>
> **Descriptivos o estructurales:**
> Indican la estructura y significado del contenido, pero no su formato. Permiten crear documentos con estructura jerárquica. Ejemplo: XML y derivados como RDF y XTM.
>
> **Híbridos:**
> Combinan marcas de presentación y estructura. Usados en la web para dar formato y estructura a la vez. Ejemplos: HTML, XHTML y WML.
>
> Los más relevantes son **HTML** (para crear páginas web) y **XML** (para estructurar e intercambiar datos).

### 4. Indica los distintos ámbitos de aplicación de los lenguajes de marcas.
> - **Desarrollo web:**
> Usados para crear páginas web, siendo HTML el lenguaje principal.
>
> - **Ámbito científico:**
> Para representar fórmulas matemáticas complejas con MathML.
>
> - **Gráficos vectoriales:**
> Se utiliza SVG para crear gráficos escalables sin pérdida de calidad.
>
> - **Metainformación:**
> Describen datos del contenido como título, autor y palabras clave.
>
> - **Bases de datos:**
> Facilitan el almacenamiento y estructuración de datos, como ocurre con XML.
>
> - **Intercambio de información:**
> Permiten compartir grandes volúmenes de datos entre diferentes plataformas.
>
> - **Mensajería:**
> Se usan para estructurar y leer documentos electrónicos en mensajes, facilitando su interpretación.
>
>Estos ámbitos muestran la versatilidad y amplio uso de los lenguajes de marcas en distintas áreas tecnológicas.

### 5. Inserta un trozo de código de cada uno de los lenguajes de marcas que se indican a continuación. Añadir a cada trozo de código un pequeño resumen sobre su estructura y la aplicación asociada que los procesa:

- **HTML** 
  
![alt](Ejemplo_cod_HTML.png)

>La estructura HTML de una página web se compone de las etiquetas <html>, que indica el comienzo de la página; <head>, que contiene información más descriptiva sobre el sitio; y <body>, que conforma todos los elementos visibles de la página.

- **iCalendar**

![alt](Ejemplo_cod_iCalendar.png)

> La estructura del código iCalendar se inicia con BEGIN:VCALENDAR, que marca el comienzo del calendario. Incluye propiedades como VERSION y CALSCALE. Cada evento dentro del calendario comienza con BEGIN:VEVENT y finaliza con END:VEVENT, conteniendo detalles como SUMMARY, DTSTART (fecha y hora de inicio) y DTEND (fecha y hora de finalización). Finalmente, el calendario concluye con END:VCALENDAR.

- **vCard** 
  
![alt](Ejemplo_cod_vCard.png)

> La estructura del código vCard comienza con BEGIN:VCARD, que marca el inicio de la tarjeta de contacto. Incluye propiedades como VERSION y FN (nombre completo). También puede contener TEL (teléfono), EMAIL (correo electrónico) y ADR (dirección). Finaliza con END:VCARD, que indica el cierre de la tarjeta.

- **KML**

![alt](Ejemplo_cod_KML.png)

> La estructura del código KML comienza con `<?xml version="1.0" encoding="UTF-8"?>` y sigue con `<kml>`. Dentro de `<kml>`, se encuentra `<Document>`, que incluye elementos como `<name>` y `<description>`. Los elementos geoespaciales se definen con `<Placemark>`. El archivo termina con `</Document>` y `</kml>`.
  
- **RSS**

![alt](Ejemplo_cod_RSS.png)

> La estructura del código RSS comienza con `<?xml version="1.0" encoding="UTF-8"?>` y sigue con `<rss>`. Dentro de `<rss>`, se encuentra `<channel>`, que incluye `<title>`, `<link>` y `<description>`. Cada artículo se define con `<item>`, que contiene su propio `<title>`, `<link>` y `<description>`. El archivo termina con `</channel>` y `</rss>`.

