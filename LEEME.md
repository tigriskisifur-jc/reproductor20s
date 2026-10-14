# Reproductor 20s — app instalable (PWA)

Archivos: index.html, manifest.webmanifest, sw.js, carpeta icons/ y .nojekyll.
Súbelos TODOS a la raíz de tu repositorio (sin meterlos dentro de otra carpeta).

## Publicar en GitHub Pages
1. Crea una cuenta en https://github.com (gratis).
2. Toca "New repository". Nombre: reproductor20s. Público. Crear.
3. "uploading an existing file": arrastra todo el contenido de esta carpeta
   (incluida la carpeta icons y el archivo .nojekyll) y pulsa "Commit changes".
4. Settings > Pages > Source: "Deploy from a branch" > Branch: main, carpeta "/ (root)" > Save.
5. Espera 1-2 minutos. Tu app quedará en https://TU-USUARIO.github.io/reproductor20s/

## Instalar en el celular
- iPhone: abre el enlace en Safari > Compartir > Añadir a pantalla de inicio.
- Android: abre el enlace en Chrome > menú ⋮ > Instalar app.
Abre la app una vez con internet; desde ahí funciona sin conexión.

## Actualizar
Si cambias index.html, edita sw.js y cambia VERSION = 'v1' por 'v2' (y así sucesivamente).
