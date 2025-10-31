# 📓 Documentación de Clase: Maquetación HTML5

### 1. Configuración del Proyecto e HTML Básico

Se inició el proyecto en el editor de código Visual Studio Code.
* Se creó la carpeta del proyecto, llamada `appElMonje`.
* Dentro de ella, se creó el archivo principal `index.html`.

<img width="886" height="466" alt="image" src="https://github.com/user-attachments/assets/0d6a10c3-232f-4e56-a17c-1cd9c1ab3bf9" />


* Se escribió la estructura HTML5 base en `index.html`, incluyendo:
    * La declaración `<!DOCTYPE html>`.
    * Las etiquetas `<html>`, `<head>` y `<body>`.
    * Metaetiquetas esenciales para la codificación (`charset="UTF-8"`) y el diseño adaptable (`viewport`).
    * Un título para la página: `<title>Pagina de Inicio Turismo</title>`.

<img width="886" height="465" alt="image" src="https://github.com/user-attachments/assets/224f16fc-edc4-4c26-b35d-f9e0eea3802c" />


### 2. Verificación Inicial en Navegador

* Se cargó el archivo `index.html` en el navegador usando un servidor local (en la dirección `127.0.0.1/appElMonje/`).
* Se utilizaron las Herramientas de Desarrollador (DevTools) del navegador para inspeccionar la estructura inicial del DOM (Modelo de Objetos del Documento), donde se pueden ver las etiquetas semánticas como `<header>`, `<nav>` y `<section>`.

<img width="886" height="465" alt="image" src="https://github.com/user-attachments/assets/fc0e0ced-78b6-41c3-88b6-342bb283f83a" />


### 3. Creación y Aplicación de Estilos CSS

Se creó un archivo CSS separado, `estilos.css`, para dar diseño a la página.

* **Estilos Generales:**
    * Se aplicó un reseteo básico para quitar todos los márgenes y rellenos por defecto: `* { padding: 0; margin: 0; }`.
    * Al `<body>`, se le asignó una fuente (`font-family: Arial, Helvetica, sans-serif;`) y un color de fondo (`background-color: blanchedalmond;`).

* **Estilos de la Cabecera (`.cabeceraPrincipal`):**
    * Se le dio un fondo azul (`background-color: blue;`) y color de texto blanco (`color: white;`).

<img width="886" height="467" alt="image" src="https://github.com/user-attachments/assets/368fd5fb-6d8d-4c13-b3f7-d4bfbe24765b" />


* **División de la Cabecera:**
    * `.cabeceraPrincipal .logotipo`: Se le asignó un fondo azul, color blanco, un ancho del 30% (`width: 30%;`) y se usó `display: inline-block;`.
    * `.cabeceraPrincipal .busqueda`: Recibió los mismos estilos (`width: 30%;`, `display: inline-block;`) para crear un diseño de dos columnas.

* **Estilos del Menú de Navegación (`.menuPrincipal`):**
    * Al contenedor del menú se le dio un fondo rojo (`background-color: red;`), texto centrado (`text-align: center;`) y relleno (`padding: 10px;`).
    * A los enlaces (`a`) dentro del menú se les cambió el color, se les quitó el subrayado y se les añadió relleno.

* **Estilos de Otras Secciones:**
    * Se definieron estilos para un "slider" (`.section.sliderPrincipal`) con fondo marrón y texto color aqua.

<img width="886" height="468" alt="image" src="https://github.com/user-attachments/assets/79b0552e-6e8a-4d02-9389-84e919afadf3" />
