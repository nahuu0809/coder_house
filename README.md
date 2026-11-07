# LemmonDrinks

Sitio web de una tienda ficticia de bebidas, hecho como primer proyecto del curso de **Desarrollo Web de Coderhouse**. Es un sitio estático con varias páginas: inicio, productos, carrito y pago, contacto, ayuda e inicio de sesión.

## Páginas

| Archivo | Contenido |
| --- | --- |
| `index.html` | Inicio con descuentos del mes y marcas |
| `products.html` | Catálogo por categoría: vinos, vodka, cerveza y más |
| `checkout.html` / `pay.html` | Carrito y pantalla de pago (formularios de demostración, sin pago real) |
| `contact.html`, `help.html`, `about.html` | Contacto, ayuda y quiénes somos |
| `login.html` | Inicio de sesión (maqueta, sin backend) |
| `404.html` | Página de error |

## Tecnologías

- HTML5, CSS y **SASS** (`css/scss`, compilado con `node-sass`)
- **Bootstrap 5**
- JavaScript (`js/card.js`) y Google Fonts
- Imágenes convertidas a `.webp` y video a `.webm` (FFmpeg y XnConvert)
- Git y GitHub Pages para publicarlo

## Ejecutar

Es un sitio estático: abrí `index.html` en el navegador, o servilo con cualquier servidor local.

Para modificar los estilos:

```bash
npm install
npm run build-css     # compila css/scss/style.scss a css/style.css
npm run watch-css     # recompila al guardar
```

## Notas

- Proyecto de aprendizaje de 2021. Los datos de contacto y de pago son de ejemplo.
- Las marcas y las imágenes se usan solo con fines educativos.
- `node-sass` está discontinuado. Si falla la instalación, usá `sass` (Dart Sass) con el mismo comando.
