# Descripción General

Este repositorio es una recopilación integral de apuntes, ejemplos y recursos para el desarrollo con JavaScript, con un enfoque en herramientas y frameworks modernos como Vite, Angular y Supabase. Está estructurado como un proyecto de Jupyter Notebook, lo que permite un aprendizaje interactivo y la experimentación.

## Contenidos

- **Conceptos Básicos y Avanzados de JavaScript**: Principios clave, patrones y mejores prácticas.
- **Vite**: Configuración, casos de uso y ejemplos de proyectos usando esta herramienta de construcción rápida.
- **Angular**: Conceptos principales, desarrollo basado en componentes, servicios y enrutamiento.
- **Supabase**: Integración de bases de datos, autenticación y APIs para aplicaciones web modernas.

## Propósito

Este repositorio está destinado a:
- Desarrolladores que buscan mejorar su comprensión de JavaScript y herramientas relacionadas.
- Estudiantes explorando Vite, Angular o Supabase en contextos prácticos.
- Cualquiera que desee construir una base de conocimiento o un portafolio con Jupyter Notebooks interactivos.

## Cómo Usarlo

1. Clona el repositorio:
   ```bash
   git clone https://github.com/bena-sudo/book.git
   ```
2. Instala Jupyter Notebook o JupyterLab (si aún no lo tienes instalado).
3. Instala Deno como intérprete:
   ```bash
   curl -fsSL https://deno.land/install.sh | sh
   deno jupyter --unstable
   deno jupyter --install
   ```
4. Abre los notebooks en Jupyter o Visual Studio Code con la extensión de Jupyter, seleccionando Deno como Kernel.

## Construir el Libro para la Web

1. Instala la herramienta necesaria:
   ```bash
   sudo pip install -U jupyter-book
   ```
2. Construye el libro:
   ```bash
   jupyter-book build .
   ```

Alternativamente, una versión preconstruida de este libro está disponible y se actualiza regularmente en:
[GitHub Pages - Libro](https://bena-sudo.github.io/book/intro.html).

Para publicar este libro, he utilizado GitHub Pages. El despliegue está automatizado con un GitHub Action desde la rama master. Los detalles del action están disponibles aquí: [GitHub Pages Overwriter](https://github.com/marketplace/actions/github-pages-overwriter). Además, se incluye un archivo `.nojekyll` para evitar que GitHub transforme la estructura del sitio y para permitir subdirectorios que comiencen con `_`. 