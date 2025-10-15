# desafio-csrf.github.io

Proyecto para el desafío de CSRF: Extracción de dimensiones de imagen y cálculo de nivel con MD5.

## Descripción

Esta página web realiza un ataque CSRF para obtener las dimensiones de la imagen de perfil de un usuario en el sitio "Imagen Importante", calcula el nivel (ancho × alto) y genera el hash MD5 del mismo.

## Cómo funciona

- La página carga la imagen desde el endpoint objetivo.
- Extrae las dimensiones naturales de la imagen.
- Calcula el nivel como ancho × alto.
- Computa el MD5 del nivel usando JavaScript.
- Muestra los resultados.

## Acceso

Visita: https://feligomez02.github.io/desafio-csrf/

## Desarrollo local

Para probar localmente:

1. Clona el repositorio.
2. Abre `index.html` en un navegador (o usa un servidor local).

Nota: Requiere conexión a internet para cargar la imagen del sitio objetivo.
