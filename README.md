# 🎮 GameVault

Tienda demo de consolas, mandos, accesorios y juegos. Todo está en una sola página: `index.html` (HTML + CSS + JavaScript, sin instalar nada).

## Funciones
- Catálogo con búsqueda, filtros, orden y control de stock
- Carrito con **métodos de pago**: Tarjeta, Yape, Plin, PayPal, PagoEfectivo y Transferencia
- 20 productos (consolas, mandos y 14 accesorios) y 12 juegos
- Guía en video con subtítulos y narración opcional
- Ofertas, FAQ, estado de pedido, favoritos y lámpara gamer (tecla `L`)

> ⚠️ Es una **simulación**: no procesa pagos reales. El QR, el número de Yape/Plin y las cuentas bancarias son de ejemplo. Tarjeta de prueba: `4111 1111 1111 1111`.

## Cómo verla
- Abre `index.html` en el navegador, o
- Publícala con **GitHub Pages**: *Settings → Pages → Deploy from a branch → `main` / `(root)`*.

## Videos de YouTube (opcional)
En `index.html`, busca `VIDEOS_YT = []` y agrega objetos `{ id, title, desc }`.

## Tecnologías
Tailwind CSS (CDN), Font Awesome, Google Fonts y JavaScript puro.
