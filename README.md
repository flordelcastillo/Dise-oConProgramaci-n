# Encuentro de Diseño de Comunicación
## Diseño de Comunicación y Programación: un cruce entre carreras para potenciarnos
### 10 de Mayo de 2024
## Presentación breve sobre qué es HTML, su importancia en la web y por qué es esencial para cualquier diseñador entenderlo.

HTML es el lenguaje estándar utilizado para crear y diseñar páginas web. Funciona mediante una estructura de etiquetas que define el contenido de una página, como texto, imágenes, enlaces y otros elementos multimedia.

Su importancia en el mundo digital es fundamental, ya que es la base sobre la cual se construyen todas las páginas web. HTML proporciona la estructura básica y el esqueleto de una página, permitiendo luego la incorporación de estilos (CSS) y funcionalidades dinámicas (JavaScript) para mejorar la experiencia del usuario.

Para un diseñador de comunicación, comprender HTML es esencial para crear experiencias web efectivas, accesibles y optimizadas, también experiencias de usuario increíbles lo que contribuye a cumplir los objetivos de comunicación de manera eficaz y persuasiva en el entorno digital actual.

## ¿Por qué una demostración de un portafolio?

Un portafolio en línea creado con HTML es fácilmente accesible desde cualquier dispositivo con conexión a internet. Los empleadores y clientes potenciales pueden acceder al contenido en cualquier momento y desde cualquier lugar, lo que aumenta la visibilidad y la probabilidad de ser visto. Además, presentar un portafolio puede diferenciar a un diseñador de comunicación en un mercado competitivo.

Al crear su portafolio con HTML, los diseñadores tienen la oportunidad de optimizar el sitio web para motores de búsqueda, lo que puede mejorar su visibilidad en línea y ayudar a que su trabajo sea descubierto por clientes potenciales y empleadores.

## Teórico

- `<!DOCTYPE html>`: Esto declara que el documento es de tipo HTML5.
- `<html lang="es">`: Define la estructura del documento HTML y especifica que el idioma utilizado es español (`lang="es"`).
- `<head>`: Aquí se incluyen metadatos y enlaces a recursos externos como hojas de estilo CSS y scripts JavaScript.
    - `<meta charset="UTF-8">`: Define la codificación de caracteres del documento como UTF-8, que es una codificación de caracteres Unicode.
    - `<title>2. Portafolio de Florencia</title>`: Define el título de la página que aparecerá en la pestaña del navegador.
- `<body>`: Contiene todo el contenido visible de la página.
    - `<header>`: Sección que contiene el encabezado de la página.
        - `<h1>Portafolio de Florencia</h1>`: Encabezado principal de la página.
    - `<nav>`: Sección de navegación que contiene enlaces a diferentes partes de la página.
        - `<a href="#acerca-de">Acerca de mí</a>`, `<a href="#proyectos">Proyectos</a>`, `<a href="#contacto">Contacto</a>`: Enlaces que llevan a secciones específicas de la página utilizando identificadores de sección.
    - `<section id="acerca-de">`: Sección que contiene información sobre Florencia.
        - `<h2>Acerca de mí</h2>`: Encabezado de la sección.
        - `<p>¡Hola! Soy Florencia...</p>`: Información sobre Florencia, su carrera y experiencia.
    - `<section id="proyectos">`: Sección que muestra algunos de los proyectos de Florencia.
        - `<h2>Proyectos</h2>`: Encabezado de la sección.
        - `<ul>`: Lista no ordenada que contiene enlaces a proyectos.
            - `<li><a href="URL">Nombre del proyecto</a></li>`: Elementos de lista que contienen enlaces a proyectos específicos.
    - `<section id="contacto">`: Sección que proporciona información de contacto de Florencia.
        - `<h2>Contacto</h2>`: Encabezado de la sección.
        - `<ul>`: Lista no ordenada que contiene información de contacto.
            - `<li>Email: correo electrónico</li>`, `<li>Teléfono: número de teléfono</li>`, `<li>Redes Sociales: ...</li>`: Elementos de lista que contienen información de contacto.
    - `<footer>`: Sección que contiene información de pie de página.
        - `<p>Derechos de autor © 2024 Florencia. Todos los derechos reservados.</p>`: Información de derechos de autor.

---

## Práctico

```css
body {
    font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    margin: 0;
    background-color: #f4f4f4;
  }
```

- Selecciona el elemento `body` de la página y define sus estilos:
    - `font-family`: Establece una serie de fuentes de sistema y fuentes web como opciones para la tipografía de la página.
    - `margin: 0;`: Elimina los márgenes predeterminados del cuerpo para asegurarse de que no haya espacios adicionales alrededor del contenido.
    - `background-color: #f4f4f4;`: Establece el color de fondo del cuerpo en un tono de gris claro.

```css
header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
```

- Establece los estilos para el elemento `header`:
    - `background-color: #333;`: Establece el color de fondo del encabezado en un tono oscuro.
    - `color: #fff;`: Establece el color del texto en blanco.
    - `padding: 20px;`: Agrega un espacio interno de 20 píxeles alrededor del contenido del encabezado.
    - `text-align: center;`: Centra el texto dentro del encabezado.

```css
nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }
```

- Define los estilos para el elemento `nav` que contiene los enlaces de navegación:
    - `background-color: #444;`: Establece el color de fondo del área de navegación en un tono más oscuro.
    - `padding: 10px;`: Agrega un espacio interno de 10 píxeles alrededor del contenido del área de navegación.
    - `text-align: center;`: Centra los enlaces de navegación dentro del área de navegación.

```css
nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
        }
```

- Define los estilos para los enlaces dentro del área de navegación:
    - `color: #fff;`: Establece el color del texto de los enlaces en blanco.
    - `text-decoration: none;`: Elimina el subrayado predeterminado de los enlaces.
    - `padding: 10px 20px;`: Agrega un espacio interno de 10 píxeles arriba y abajo, y 20 píxeles a la izquierda y derecha, alrededor del texto de los enlaces.

```css
nav a:hover {
            background-color: #555;
        }
```

- Define los estilos para los enlaces cuando se pasa el cursor sobre ellos:
    - `background-color: #555;`: Cambia el color de fondo de los enlaces a un tono más oscuro cuando el cursor está sobre ellos.

```css
section {
            padding: 20px;
            margin: 20px;
            background-color: #fff;
            border-radius: 15px;
        }
```

- Define los estilos para los elementos `section` que contienen el contenido de la página:
    - `padding: 20px;`: Agrega un espacio interno de 20 píxeles alrededor del contenido de cada sección.
    - `margin: 20px;`: Agrega un espacio externo de 20 píxeles alrededor de cada sección.
    - `background-color: #fff;`: Establece el color de fondo de cada sección en blanco.
    - `border-radius: 15px;`: Agrega esquinas redondeadas a cada sección con un radio de 15 píxeles.

```css
footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
```

- Define los estilos para el elemento `footer` que contiene el pie de página:
    - `background-color: #333;`: Establece el color de fondo del pie de página en un tono oscuro.
    - `color: #fff;`: Establece el color del texto en blanco.
    - `text-align: center;`: Centra el texto dentro del pie de página.
    - `padding: 20px;`: Agrega un espacio interno de 20 píxeles alrededor del contenido del pie de página.
