# Élite Time · Relojería original

Sitio web de Élite Time, tienda de relojes originales en Barranquilla (Invicta, Technomarine, Curren y Poedagar).

## Páginas

| Archivo | Contenido |
|---|---|
| `index.html` | Inicio: intro animada, reloj con la hora de Barranquilla, selección de la semana, marcas, clientes |
| `coleccion.html` | Catálogo con filtros por marca, línea, género y precio |
| `reloj.html#r001` | Ficha de cada reloj, elección de caja y compra por WhatsApp |
| `marcas.html` | Las cuatro marcas |
| `clientes.html` | Video y fotos de entregas reales |
| `perfumes.html` | Perfumería original (próximamente) |
| `comprar.html` | Cómo comprar, garantía y preguntas frecuentes |

## Datos

- Productos: `data/productos.json`
- Estilos y lógica compartida: `assets/css/elite.css` y `assets/js/elite.js`
- Pedidos: botón de WhatsApp y carrito que arma el mensaje al **310 530 0899**

El catálogo vive en una base de datos de Cloudflare (D1) y se edita desde el panel, que está publicado aparte en Cloudflare Pages. La tienda lee los productos de la API del panel; si no responde, usa la copia de `data/productos.json`.

Es un sitio estático: no necesita compilación. Se publica tal cual en GitHub Pages o en cualquier hosting.
