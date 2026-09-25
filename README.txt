DYSONRESTORE REPARACIÓN SERVICIO TÉCNICO EN ELCHE
=================================================

Web de una sola página (HTML/CSS/JS estático + función serverless en Vercel)
para DysonRestore, servicio técnico y reparación de equipos Dyson con recogida
y entrega en Elche y área metropolitana.

Dominio: https://elcheserviciotecnico.com.es/
Marca: DysonRestore Reparación Servicio Técnico en Elche
Nombre corto (og:site_name): DysonRestore – Elche
Ficha de Google: https://maps.app.goo.gl/gNwqvtLq8mgjmR9s9
Mapa: iframe de Google Maps de la ficha "DysonRestore Reparación Servicio Técnico",
insertado tal cual en la sección de contacto (ancho 100% vía CSS).

DATOS DE CONTACTO
- WhatsApp: +34 649 97 01 28.
- Teléfono: +34 910 05 48 17.
- Recogida a domicilio: https://sis.redsys.es/tiendaWeb/item/NDk4OzI=
  (botón "Solicita tu recogida ahora" del hero, siempre en negro).
- Horario: lunes a viernes de 09:30 a 18:00.
- Política de privacidad: https://kelatos.com/privacy-policy/.

DIRECCIÓN: no se muestra dirección postal. La web indica "Elche y área
metropolitana" y servicio de recogida y entrega; el taller está en Madrid.
Si se confirma una dirección en Elche, añadirla al hero, footer y JSON-LD.

ESTRUCTURA
- index.html: toda la página (hero, ventajas, reparación rápida, confianza,
  servicios, por qué elegirnos, cómo trabajamos, contacto + mapa, FAQ, texto
  SEO, footer, cookies y JSON-LD).
- style.css: base de la plantilla.
- mobile-navigation.css, social-footer.css, cal-booking.css: ajustes compartidos.
- dysonrestore.css: identidad visual de la marca (una sola capa, sin
  sobrescrituras en cascada).
- dysonrestore-header-hero.css: cabecera grafito con logotipo blanco.
- dysonrestore.js: menú móvil (se cierra al pulsar un enlace), formulario y
  preferencias de cookies (clave localStorage "dysonrestore_cookie_preference").
- dysonrestore-n8n-chat.js / .css: chatbot n8n con webhook compartido del grupo
  y botón de respaldo.
- api/contacto.js: envío del formulario por SMTP (variables SMTP_HOST,
  SMTP_PORT, SMTP_SECURE, SMTP_USER, SMTP_PASS y CONTACT_EMAIL en Vercel).
- img/: isotipo, patrón e ilustraciones SVG de la marca.
- robots.txt y sitemap.xml apuntan a https://elcheserviciotecnico.com.es/.

PALETA: lima eléctrica, grafito y gris acero (estética tecnológica).
- Lima #9BD60A · oscuro #7FB305 · oliva muy oscuro #2F4A06 (franja superior, sección oscura)
- Lima de texto #4D7C0F para títulos en cursiva, enlaces e iconos sobre fondo claro
- Texto negro #141619 sobre botones lima (el blanco sobre lima no es legible)
- Grafito #141619 (cabecera, footer, cookies, tarjeta de Google, botón de teléfono y chat)
- El botón de teléfono y el del chat van en grafito con detalle lima para no
  confundirse con el verde de WhatsApp.
Excepciones: WhatsApp conserva su verde y YouTube su rojo corporativo.
En móvil (≤720px) no se muestran las ilustraciones laterales del hero.
