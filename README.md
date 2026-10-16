# Un pastel para ti

Juego web para móvil, estilo Cooking Mama, en un solo archivo: `index.html`.
No necesita servidor, build ni librerías. Las fuentes (Fredoka y Nunito) se cargan
de Google Fonts si hay internet; sin conexión usa las del sistema.

## Personalizar

Abre `index.html` y edita el bloque `CONFIG` al inicio del `<script>`:

- `nombre`: nombre de tu novia (aparece en la portada y en el título final).
- `firma`: cómo firmas el mensaje.
- `velas`: número de velas (1 a 9).
- `tituloFinal`: título de la pantalla final; `{nombre}` se reemplaza solo.
- `mensaje`: lista de párrafos del mensaje final.
- `sonidos`: `true` o `false`.

Los colores están en las variables `:root` del `<style>`.

## Pasos del juego

1. Mezclar: dibujar círculos sobre el tazón.
2. Huevos: tocar cada huevo dos veces.
3. Verter: mantener presionado y soltar en la zona verde.
4. Hornear: sacar el pastel cuando el indicador está en la zona dorada.
5. Cubrir: elegir sabor de betún y deslizar el dedo sobre el pastel.
6. Decorar: arrastrar decoraciones al pastel (mínimo 6).
7. Velas: encender cada vela y mantener presionado para soplar.

Al final aparece el pastel terminado, confeti y el mensaje.

## Archivos

- `index.html`: versión actual (estilo juego móvil, hecha a partir de `refs/01-mezclar.png`).
- `index-v1.html`: primera versión (estilo claymorphism simple), por si quieres compararla.
- `refs/`: imágenes de referencia generadas con IA. Si agregas más pantallas aquí,
  el flujo es: imagen de referencia, análisis, código.

## Cómo llevarlo a su teléfono

- Opción simple: sube `index.html` a un hosting estático gratuito
  (Netlify Drop, Vercel, GitHub Pages) y envíale el enlace.
- Opción local: enviar el archivo por WhatsApp o correo y abrirlo con el
  navegador del teléfono. Algunos teléfonos abren los .html como texto, por eso
  el enlace es más fiable.
- En el teléfono, "Añadir a pantalla de inicio" lo abre a pantalla completa.
