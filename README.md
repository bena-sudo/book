# JavaScript, Vite, Angular, and Supabase Notes Repository

## English Version

### Overview

This repository serves as a comprehensive collection of notes, examples, and resources for JavaScript development, with a focus on modern tools and frameworks such as Vite, Angular, and Supabase. It is structured as a Jupyter Notebook project, allowing interactive learning and experimentation.

### Contents

- **JavaScript Basics and Advanced Concepts**: Key principles, patterns, and best practices.
- **Vite**: Configuration, use cases, and project examples using this fast build tool.
- **Angular**: Core concepts, component-based development, services, and routing.
- **Supabase**: Integration of database, authentication, and APIs for modern web apps.

### Purpose

This repository is intended for:
- Developers looking to enhance their understanding of JavaScript and related tools.
- Learners exploring Vite, Angular, or Supabase in practical contexts.
- Anyone building a knowledge base or portfolio with interactive Jupyter Notebooks.

### How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/bena-sudo/frontend-book.git
   ```
2. Install Jupyter Notebook or JupyterLab (if not already installed).
3. Install Deno as the interpreter:
   ```bash
   curl -fsSL https://deno.land/install.sh | sh
   deno jupyter --unstable
   deno jupyter --install
   ```
4. Open the notebooks in Jupyter or Visual Studio Code with the Jupyter extension, selecting Deno as the kernel.

### Building the Book for Web

1. Install the required tool:
   ```bash
   sudo pip install -U jupyter-book
   ```
2. Build the book:
   ```bash
   jupyter-book build book
   ```

Alternatively, a prebuilt version of this book is available and updated regularly at:
[GitHub Pages - Book](https://bena-sudo.github.io/book/intro.html).

To publish the book, GitHub Pages is used. The deployment is automated using a GitHub Action from the master branch. Details about the action can be found here: [GitHub Pages Overwriter](https://github.com/marketplace/actions/github-pages-overwriter). Additionally, a `.nojekyll` file is included to prevent GitHub from transforming the site structure and to allow subdirectories starting with `_`.

---

## Versión en Español

### Descripción General

Este repositorio es una recopilación integral de apuntes, ejemplos y recursos para el desarrollo con JavaScript, con un enfoque en herramientas y frameworks modernos como Vite, Angular y Supabase. Está estructurado como un proyecto de Jupyter Notebook, lo que permite un aprendizaje interactivo y la experimentación.

### Contenidos

- **Conceptos Básicos y Avanzados de JavaScript**: Principios clave, patrones y mejores prácticas.
- **Vite**: Configuración, casos de uso y ejemplos de proyectos usando esta herramienta de construcción rápida.
- **Angular**: Conceptos principales, desarrollo basado en componentes, servicios y enrutamiento.
- **Supabase**: Integración de bases de datos, autenticación y APIs para aplicaciones web modernas.

### Propósito

Este repositorio está destinado a:
- Desarrolladores que buscan mejorar su comprensión de JavaScript y herramientas relacionadas.
- Estudiantes explorando Vite, Angular o Supabase en contextos prácticos.
- Cualquiera que desee construir una base de conocimiento o un portafolio con Jupyter Notebooks interactivos.

### Cómo Usarlo

1. Clona el repositorio:
   ```bash
   git clone https://github.com/bena-sudo/frontend-book.git
   ```
2. Instala Jupyter Notebook o JupyterLab (si aún no lo tienes instalado).
3. Instala Deno como intérprete:
   ```bash
   curl -fsSL https://deno.land/install.sh | sh
   deno jupyter --unstable
   deno jupyter --install
   ```
4. Abre los notebooks en Jupyter o Visual Studio Code con la extensión de Jupyter, seleccionando Deno como Kernel.

### Construir el Libro para la Web

1. Instala la herramienta necesaria:
   ```bash
   sudo pip install -U jupyter-book
   ```
2. Construye el libro:
   ```bash
   jupyter-book build book
   ```

Alternativamente, una versión preconstruida de este libro está disponible y se actualiza regularmente en:
[GitHub Pages - Libro](https://bena-sudo.github.io/book/intro.html).

Para publicar este libro, he utilizado GitHub Pages. El despliegue está automatizado con un GitHub Action desde la rama master. Los detalles del action están disponibles aquí: [GitHub Pages Overwriter](https://github.com/marketplace/actions/github-pages-overwriter). Además, se incluye un archivo `.nojekyll` para evitar que GitHub transforme la estructura del sitio y para permitir subdirectorios que comiencen con `_`. 
