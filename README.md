# Sitio web – Punta Diamantes (propuesta)

Un solo archivo `index.html` más la carpeta `img/`. No necesita servidor ni base de datos:
se sube tal cual a cualquier hosting (Netlify, Vercel, GitHub Pages, cPanel…).

## Identidad visual (tomada del logo y redes oficiales)
| Elemento | Valor |
|---|---|
| Rosa de marca (fondo del logo) | `#E54583` |
| Rosa oscuro (hover / texto) | `#C9306D` |
| Ciruela oscuro (contraste, pie de página) | `#2B1A24` |
| Amarillo (fachadas, estrellas) | `#F2B33D` |
| Títulos – similar a "Punta" del logo | DM Serif Display |
| Acentos manuscritos – similar a "Diamantes" | Satisfy |
| Texto | Manrope |

Logo: `img/logo-blanco.png` y `img/logo-rosa.png` (extraídos de su foto de perfil, fondo transparente).
Ícono: `img/diamante-blanco.png`.

## Fotos
Las fotos actuales son las del hotel publicadas en Trip.com (máximo 960 px).
**Pídale al hotel las fotos originales en alta resolución** y reemplácelas con el mismo nombre de archivo:
la portada y la sección Day Pass se verán mucho más nítidas.

## Cambios rápidos (al inicio del `<script>`)
- `WHATSAPP` → número que recibe las reservaciones (503 + número).
- `AMENITIES` → servicios (ícono, título, descripción).
- `ROOMS` → habitaciones (nombre, foto, texto, capacidad).
- `GALLERY` → fotos de la galería, categoría y tamaño (`w` ancha, `t` alta).

## Precios
Los precios de habitaciones están en `ROOMS` (campo `price`, en US$ por noche; `null` muestra "Consultar").
Valores actuales de referencia tomados de plataformas de reserva: Booking.com desde US$50 (2 adultos) y Hoteles.com US$55.
Cámbielos por las tarifas oficiales del hotel. La nota debajo de las habitaciones está en `PRICE_NOTE`.

## Por confirmar con el hotel
- Tarifas oficiales por habitación y precio del Day Pass.
- Tipos exactos de habitación y capacidad.
- Horario: Instagram dice 7:00 a. m. a 8:00 p. m.; otra fuente dice 9:00 a. m. a 5:00 p. m.
- Platos del menú.
