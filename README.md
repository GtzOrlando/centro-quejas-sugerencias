# Buzón de Quejas y Sugerencias - Reto 2 UVEG Módulo Despliegue de aplicaciones web

## Descripción del Proyecto
Aplicación web estática que simula un buzón de quejas y sugerencias. Cuenta con una interfaz dividida en dos roles: un formulario público para la captura de quejas o sugerencias por parte de los usuarios y un panel administrativo para visualizar y eliminar las quejas enviadas. En esta primera fase, los datos se gestionan localmente a través de `localStorage` y se visualizan de manera estática en GitHub.

## Proceso de Preparación y Optimización

Para garantizar el rendimiento y orden del proyecto, se aplicaron las siguientes medidas:

*   **Minificación de Código:** Los archivos fuente (`style.css` y `app.js`) fueron procesados para remover espacios, comentarios y saltos de línea. El archivo `index.html` fue actualizado para consumir exclusivamente las versiones optimizadas (`style.min.css` y `app.min.js`), reduciendo el tiempo de carga.
*   **Optimización de Imágenes:** Se implementó el logotipo del proyecto (`logo-ogb.svg`) utilizando el formato vectorial SVG, lo que garantiza un peso en kilobytes mínimo y escalabilidad sin pérdida de resolución.

## Versionamiento del Proyecto

El proyecto se encuentra bajo control de versiones utilizando Git.

## Configuración del Servidor Web (Local)

El despliegue local se configuró utilizando el servidor web **Apache** mediante XAMPP. 

**Configuración del Virtual Host aplicado:**
Se usa el puerto 80 en apache para conexión local.
