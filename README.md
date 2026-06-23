Taller 3 - Bootstrap y GitHub

Descripción

Este proyecto corresponde a un taller práctico de maquetación web realizado con HTML5 y Bootstrap 5.
El sitio está compuesto por una página principal y varias páginas internas enlazadas entre sí, con el objetivo de practicar la organización de archivos, el diseño visual con Bootstrap y el uso de GitHub para publicar el proyecto.

Objetivo del proyecto

El objetivo principal de este trabajo es aplicar conceptos básicos de desarrollo web, entre ellos:

- Estructura de un proyecto web en varias páginas.
- Uso de Bootstrap para el diseño responsive.
- Creación de menús de navegación.
- Uso de componentes como:
  - navbar
  - carousel
  - cards
  - formularios
  - tablas
- Organización de carpetas y archivos.
- Enlaces internos entre páginas HTML.
- Publicación del proyecto en GitHub.

---

Tecnologías utilizadas

- HTML5
- Bootstrap 5
- Bootstrap Icons
- CSS en línea y clases de Bootstrap
- Git y GitHub

---

Estructura del proyecto

taller3_bootstrap_git/
│
├── index.html
├── README.md
│
├── app/
│   ├── github.html
│   ├── registro.html
│   └── tables.html
│
└── assets/
    └── img/

---

Páginas del proyecto

1. "index.html"

Es la página principal del proyecto.
Aquí se encuentra la estructura general del sitio y el menú de navegación hacia las demás páginas.

Incluye elementos como:

- barra de navegación
- menú desplegable
- carrusel de imágenes
- tarjetas
- secciones informativas
- botones
- footer

---

2. "app/github.html"

Esta página funciona como una guía visual sobre GitHub y la estructura del proyecto.

Contiene información como:

- estructura de carpetas del proyecto
- tabla descriptiva de archivos
- requisitos iniciales para trabajar con Git y GitHub
- configuración básica de Git
- comandos como:
  git init
git add .
git commit -m "Primer commit"
git push
- explicación breve de ramas como "main", "dev" y "feature"

---

3. "app/registro.html"

Página enfocada en el uso de formularios con Bootstrap.

Incluye:

- formulario de inicio de sesión
- formulario de creación de cuenta
- campos como:
  - nombre
  - fecha de nacimiento
  - correo electrónico
  - contraseña
  - checkbox de recordarme

---

4. "app/tables.html"

Página destinada a practicar tablas responsivas con Bootstrap.

Incluye una tabla de usuarios con campos como:

- ID
- nombre
- apellido
- correo
- teléfono
- ciudad
- cargo
- edad
- estado
- acción

---

Navegación entre páginas

El proyecto tiene una barra de navegación común en sus páginas.
Dentro del menú Consultas se encuentran los enlaces a:

- "github.html"
- "registro.html"
- "tables.html"

Además, desde las páginas dentro de la carpeta "app", el enlace de Inicio vuelve a la página principal con:

../index.html

---

Componentes de Bootstrap usados

En este proyecto se usaron varios componentes de Bootstrap, entre ellos:

- Navbar
- Dropdown
- Carousel
- Cards
- Grid system
- Buttons
- Forms
- Tables
- Responsive containers

---

Cómo ejecutar el proyecto

Opción 1: abrir directamente

1. Descargar el proyecto o clonarlo desde GitHub.
2. Abrir la carpeta del proyecto.
3. Ejecutar "index.html" en el navegador.

Opción 2: con Visual Studio Code

1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Instalar la extensión Live Server.
3. Abrir "index.html".
4. Ejecutar con Open with Live Server.

---

Repositorio en GitHub

Este proyecto se encuentra publicado en el siguiente repositorio:

"Repositorio del proyecto" (https://github.com/joseismael25/taller3_bootstrap_git)

---

Aprendizajes obtenidos

Con este taller se practicó:

- Maquetación web con HTML y Bootstrap.
- Uso de clases de Bootstrap para diseño rápido.
- Organización de un proyecto por carpetas.
- Creación de varias páginas enlazadas.
- Uso de tablas y formularios.
- Manejo básico de Git y GitHub.
- Publicación de un proyecto web en un repositorio.

---

Posibles mejoras

A futuro se podrían agregar mejoras como:

- separar estilos en un archivo CSS externo
- agregar validaciones con JavaScript
- mejorar la uniformidad visual entre páginas
- agregar más contenido real en lugar de texto de ejemplo
- optimizar la estructura semántica del HTML
- publicar el proyecto con GitHub Pages

---

Autor

Jose Ismael

Proyecto realizado como práctica académica de maquetación web con Bootstrap y GitHub.
