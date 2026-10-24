# Astra Print 3D

Página web de Astra Print 3D (David Mateo Robayo).

## Publicar en GitHub Pages
1. Sube `index.html` y la carpeta `imagenes/` a la raíz del repositorio.
2. En GitHub: Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)`.
3. Tu página quedará en `https://TU-USUARIO.github.io/NOMBRE-REPO/`.

## Agregar fotos a la galería
1. Copia la foto a la carpeta `imagenes/`.
2. En `index.html`, busca `var FOTOS=[` y agrega una línea:
   `{src:"imagenes/mi-foto.jpg", cap:"Descripción"},`
