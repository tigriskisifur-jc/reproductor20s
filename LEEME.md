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
Si cambias index.html, edita sw.js y cambia VERSION = 'v2' por 'v3' (y así sucesivamente).

## Novedades v2
- Biblioteca guardada en el dispositivo (no hace falta volver a cargar los archivos).
- Listas de reproducción (botón ＋ junto a cada pista, 📥 para una carpeta completa).
- Clips de hasta 120 s y crossfade de 3, 5 u 8 s.
- Botón "Instalar" dentro de la app.
Para que tu teléfono reciba la versión nueva: sube los archivos, abre la app con internet y ciérrala y ábrela de nuevo.
