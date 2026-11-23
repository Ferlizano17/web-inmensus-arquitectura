# Inmensus Arquitectura — web

Sitio estático (HTML + CSS + JS, sin dependencias). Lo creó Pura Vida IA.

- `public/index.html`: landing, cotizador y formulario (envía por WhatsApp).
- `public/legal.html`: aviso legal, privacidad (Ley 8968, Costa Rica) y cookies.
- `public/img/`: logo, fotos y favicon.
- `netlify.toml`: publica `public/`. Tiene `noindex` mientras el sitio esté en prueba.

## Configuración del cotizador
Al final de `index.html`, en el bloque `CONFIGURACIÓN`:
- `COSTO_M2`: costo directo por m² (₡390.000).
- `MOB`: precios de mobiliario por metro lineal (DE EJEMPLO, pendientes de validar).
- `WHATSAPP`: número de destino (50686530542).

## Antes de lanzar
- Quitar la franja de «versión de prueba» y los `noindex` (meta en ambos HTML y la cabecera en `netlify.toml`).
- Completar los datos amarillos de `legal.html`.
- Sustituir las imágenes de ejemplo de la galería y las opiniones pendientes.
