

BLOG (/blog):
- Los artículos NO viven en este repositorio: los genera y publica el agente SEO de Kelatos
  (Agentes V2 → organización «DysonRestore Elche», clave dysonrestoreelche) y se leen en vivo de la API
  pública de Kelatos, sin token: https://db.affirmatechnology.com/kelatos-api/publico/blog?org=dysonrestoreelche
- api/blog.js + lib/blog.js generan /blog y /blog/<slug> en el servidor copiando cabecera, aviso,
  pie, WhatsApp, chat, cookies y scripts de index.html. Estilos en blog.css.
- api/sitemap.js genera /sitemap.xml (se eliminó el sitemap.xml estático).
- Enlace «Blog» en el menú (escritorio y móvil) y en el pie.
- La web principal es www.elcheserviciotecnico.com.es (el dominio sin www redirige):
  canonical, og:url, datos estructurados y robots.txt apuntan a www.
