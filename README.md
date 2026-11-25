# BROTE UNO — Manual de uso · Kit de Huerto Urbano

Manual interactivo en español, listo para abrir en el celular y en computadora.

## Qué hay en esta carpeta

- `index.html` — El manual completo en un solo archivo. Ya trae el CSS y el JavaScript dentro, y las 9 fotos incrustadas, así que funciona solo, sin depender de otros archivos.
- `assets/` — Las 9 fotos originales con nombres claros, por si quieres reutilizarlas o cambiarlas:
  - `rabano.jpg`, `chile-jalapeno.jpg`, `albahaca.jpg`, `flor-cosmos.jpg`, `cilantro.jpg`, `chile-chiltepin.jpg`
  - `sobres-juntos.jpg`, `kit-caja.jpg`, `sustrato-brote-uno.jpg`
- `qr/brote-uno-qr-manual.png` — El QR listo para imprimir, que abre el manual público.

## Cómo abrirlo en VS Code

1. Descomprime la carpeta `brote-uno-manual`.
2. En VS Code: File > Open Folder > elige `brote-uno-manual`.
3. Abre `index.html`.
4. Para verlo en vivo, haz clic derecho en `index.html` > Open with Live Server (si tienes la extensión), o simplemente ábrelo con doble clic en el navegador.

## Cómo subirlo a GitHub

1. Crea un repositorio nuevo en GitHub, por ejemplo `brote-uno-manual`.
2. Sube todo el contenido de esta carpeta (o arrastra la carpeta en la web de GitHub, o con Git):
   ```bash
   git init
   git add .
   git commit -m "Manual BROTE UNO"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/brote-uno-manual.git
   git push -u origin main
   ```
3. Para publicarlo gratis con GitHub Pages:
   Settings del repositorio > Pages > Source: Deploy from a branch > Branch: main > Folder: / (root) > Save.
4. Tu manual quedará en `https://TU-USUARIO.github.io/brote-uno-manual/`

## Nota sobre CSS y JS

El manual se entrega como un solo `index.html` autocontenido a propósito: así no se rompen las fotos ni las animaciones al moverlo de carpeta o subirlo a GitHub Pages. El CSS y el JS están dentro del mismo archivo, entre las etiquetas `<style>` y `<script>`. Si quieres separarlos en `styles.css` y `script.js`, puedes copiar esos bloques a archivos aparte y enlazarlos desde el HTML, pero no es necesario para que funcione.

## Contenido

10 capítulos: Tu kit, Tu espacio, Sustrato, A sembrar, Fibra de coco, Cuidados, Semillas, Trasplante, Problemas y A disfrutar. Con galería táctil de semillas y índice compacto para teléfono.

BROTE UNO — @broteuno — Pequeñas semillas, grandes comienzos.
