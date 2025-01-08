# Comandos de Angular

Angular CLI es una herramienta poderosa que permite a los desarrolladores crear, desarrollar y mantener aplicaciones Angular de manera eficiente. A continuación, se presenta una lista de los comandos más importantes:

## Comandos de Inicialización

### Crear un nuevo proyecto
```bash
ng new <nombre-del-proyecto>
```
Crea una nueva aplicación Angular con la configuración inicial.

### Ayuda
```bash
ng help
```
Muestra la lista de comandos disponibles y sus descripciones.

---

## Comandos de Desarrollo

### Servidor de desarrollo
```bash
ng serve
```
Inicia un servidor de desarrollo y compila la aplicación en tiempo real. Por defecto, está disponible en `http://localhost:4200/`.

### Generar elementos (componentes, servicios, módulos, etc.)
```bash
ng generate <schematic> <nombre>
```
Alias: `ng g`

Ejemplos:
- Crear un componente:
  ```bash
  ng g component <nombre>
  ```
- Crear un servicio:
  ```bash
  ng g service <nombre>
  ```
- Crear un módulo:
  ```bash
  ng g module <nombre>
  ```
- Crear una directiva:
  ```bash
  ng g directive <nombre>
  ```
- Crear un pipe:
  ```bash
  ng g pipe <nombre>
  ```
- Crear una clase:
  ```bash
  ng g class <nombre>
  ```
- Crear una interfaz:
  ```bash
  ng g interface <nombre>
  ```
- Crear un enumerador:
  ```bash
  ng g enum <nombre>
  ```
- Crear un guard:
  ```bash
  ng g guard <nombre>
  ```

### Añadir bibliotecas
```bash
ng add <paquete>
```
Instala y configura una biblioteca Angular en el proyecto. Ejemplo:
```bash
ng add @angular/material
```

### Construcción de la aplicación
```bash
ng build
```
Compila la aplicación para producción. Los archivos generados se colocan en el directorio `dist/`.

Opciones comunes:
- Para producción:
  ```bash
  ng build --prod
  ```

---

## Comandos de Pruebas

### Pruebas unitarias
```bash
ng test
```
Ejecuta las pruebas unitarias en la aplicación utilizando Karma.

### Pruebas end-to-end (E2E)
```bash
ng e2e
```
Ejecuta pruebas end-to-end utilizando una herramienta como Protractor (descontinuado en las versiones más recientes).

---

## Comandos de Actualización

### Actualizar Angular y dependencias
```bash
ng update
```
Actualiza Angular y las dependencias del proyecto a sus versiones más recientes.

---

## Comandos de Linter

### Ejecutar el linter
```bash
ng lint
```
Analiza el código para encontrar y arreglar problemas de estilo y errores potenciales.

---

## Comandos de Depuración y Optimización

### Analizar el tamaño del bundle
```bash
ng build --stats-json
```
Luego, usar herramientas como `webpack-bundle-analyzer` para analizar el tamaño del bundle:
```bash
npx webpack-bundle-analyzer dist/stats.json
```

### Habilitar análisis en tiempo real
```bash
ng serve --source-map
```
Genera mapas de origen para facilitar la depuración.

---

## Comandos de Configuración

### Configurar Angular CLI
```bash
ng config <clave> <valor>
```
Permite establecer o modificar configuraciones globales o específicas del proyecto. Ejemplo:
```bash
ng config cli.defaultCollection @angular-eslint/schematics
```

---

## Otros Comandos Útiles

### Mostrar la versión de Angular
```bash
ng version
```
Muestra la versión de Angular CLI, Angular y otras dependencias relacionadas.

### Desplegar en un servidor
```bash
ng deploy
```
Despliega la aplicación a un servicio de hosting compatible como Firebase, Netlify, etc. Requiere configuración previa.

---

¡Con estos comandos tendrás un resumen práctico para trabajar con Angular CLI de manera eficiente!
