# Blog multipágina con imágenes preconfiguradas
- `index.html` con enlaces que se abren en **nueva pestaña** y mini-galerías.
- `escrito1.html ... escrito8.html` con sección **Galería** que ya apunta a `/images/escritoX-Y.svg`.
- Carpeta `images/` con **3 placeholders por escrito** (total 24 SVGs morados).
- `.nojekyll` para GitHub Pages.

## Reemplazar una imagen
Sustituye cualquier archivo en `images/` por tu imagen (mismo nombre). Ejemplo: reemplaza `images/escrito3-2.svg` por `images/escrito3-2.jpg` o `.png`.
Si cambias el nombre, recuerda actualizar el `src` en el HTML correspondiente.

## Publicar en GitHub Pages
1. Sube todo el contenido de esta carpeta al repositorio (incluida la carpeta `images`).
2. Settings → Pages → Deploy from a branch → `main` /(root).
3. Visita la URL pública.
