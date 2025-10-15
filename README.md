# Sitio de prueba

Esta carpeta contiene `prueba.html`, una página estática de ejemplo para hacer pruebas locales.

## Cómo servir la carpeta (PowerShell - Windows)

1. Abre PowerShell y cambia al directorio donde está este archivo:

   Set-Location -Path "C:\Users\felip\OneDrive\Documentos"

2. Opción A — si tienes Python 3 instalado (recomendado):

   python -m http.server 8000

   Esto levantará un servidor en http://localhost:8000

3. Opción B — si tienes Node.js instalado y prefieres usar http-server:

   npx http-server -p 8000

4. Abre tu navegador e ingresa a: http://localhost:8000

## Notas

- Si el puerto 8000 ya está en uso, cámbialo por otro número (por ejemplo 3000).
- En Windows PowerShell, si `python` no está en el PATH, intenta `py -3 -m http.server 8000`.
