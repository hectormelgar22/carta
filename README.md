# Carta digital premium

Carta digital para bares y restaurantes, pensada como producto comercial: un libro físico de alta gama convertido en experiencia digital, con funciones que el papel nunca podría tener.

## Stack

HTML + CSS + JavaScript vanilla. Sin frameworks, sin dependencias de build. Todo vive en un único archivo autocontenido: [`carta.html`](carta.html).

Únicas dependencias externas: Google Fonts y fotografías de demostración (Unsplash).

## Uso

Abre `carta.html` directamente en el navegador (doble clic, o arrástralo a una pestaña). No necesita servidor.

## Personalizar para un restaurante nuevo

1. Duplica `carta.html`.
2. Edita el objeto `CARTA` al inicio del `<script>`: restaurante, contacto, categorías, platos, especiales, WhatsApp.
3. Elige preset en `CARTA.theme.preset`: `gastrobar`, `cerveceria` o `cafeteria`.
4. Sustituye las fotos de demostración por las del restaurante (mantén el parámetro `w=` en la URL si usas un proveedor de imágenes con variantes por tamaño, como Unsplash o Cloudinary).

**Antes de entregar una carta a un cliente real**, cambia `CARTA.contact.whatsapp` — el valor por defecto es un número de ejemplo.

## Funciones

- Flipbook con giro de página 3D, swipe y pase rápido de sección
- Navegación por pestañas laterales e índice
- Alérgenos, picante, maridaje con venta cruzada, recomendación de la casa
- Modo mesa, pedido por WhatsApp, dividir cuenta, aviso al camarero
- Modo día/noche automático, idioma ES/EN, parallax, tres presets visuales
- Accesible (contraste AA, zonas táctiles de 44px), con fallbacks para navegadores antiguos y `prefers-reduced-motion`
