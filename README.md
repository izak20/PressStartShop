# Press Start Shop

Mockup de diseño para una tienda de videojuegos, consolas y accesorios.
Exportado desde una herramienta de diseño visual (formato Design Component /
`<x-dc>`). Tratar el markup como referencia de diseño: los valores exactos
(colores, tipografías, espaciados) viven en los atributos `style="…"` y en
el bloque `<helmet><style>` de cada página.

## Estructura

- `index.html` — página de Inicio.
- `producto.html` — página de detalle de producto (PS5 Slim).
- `assets/` — imágenes usadas por ambas páginas.
- `support.js`, `vendor/react.js`, `vendor/react-dom.js` — runtime que
  renderiza el componente en el navegador; no es parte del diseño.

## Ver el sitio

Servir la carpeta con un servidor estático (algunos navegadores bloquean
los scripts sobre `file://`) y abrir `index.html`:

```bash
python3 -m http.server
```
