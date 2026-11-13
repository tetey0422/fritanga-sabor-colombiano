# Fritanga Sabor Colombiano — Sitio web

Sitio estático (HTML puro): menú + botón de WhatsApp. Sin base de datos, sin build.

## Archivos
- index.html    → la página (menú, SEO, WhatsApp)
- og-image.jpg  → imagen que se ve al compartir el link
- robots.txt / sitemap.xml → SEO
- vercel.json   → headers de seguridad

## Publicar (GitHub + Vercel)
1. Crear repo en github.com → New repository → nombre: fritanga-sabor-colombiano
2. Subir estos archivos a la raíz del repo (Add file → Upload files)
3. En vercel.com → Add New → Project → Import el repo
4. Project Name: fritanga-sabor-colombiano
   Framework Preset: Other (dejar Build Command y Output vacíos) → Deploy
5. Cada cambio que hagas en GitHub se publica solo.

## Si Vercel te da otra URL
Si "fritanga-sabor-colombiano.vercel.app" estaba ocupada y Vercel asignó otra,
reemplaza https://fritanga-sabor-colombiano.vercel.app por la URL real en:
index.html (canonical, og:url, og:image, twitter:image, JSON-LD), robots.txt y sitemap.xml.

## Después de publicar
- Google Search Console → agregar la URL (tipo "Prefijo de URL") → enviar sitemap.xml
- Google Business Profile → negocio con área de servicio (sin dirección visible)

## Editar el menú
En index.html, cambia el precio en <p class="item-price">$XX</p>.
Para agregar un plato, copia un bloque <article class="item-card"> completo.

## WhatsApp
Número: +1 (317) 446-9148. Para cambiarlo, reemplaza 13174469148 en index.html (aparece 3 veces + schema).
