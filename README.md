# Andre's Corner

Sitio web básico para pruebas de la WhatsApp Business API / Cloud API de Meta.

## Contenido

- `index.html` — página principal
- `privacy.html` — Política de Privacidad (requerida por Meta)
- `terms.html` — Términos de Servicio
- `style.css` — estilos compartidos

## Antes de enviarlo a revisión de Meta

1. Reemplaza los datos de contacto de ejemplo (correo, teléfono, dirección) en
   `index.html`, `privacy.html` y `terms.html` por los reales del negocio.
2. Ajusta el texto de `privacy.html` y `terms.html` para que refleje con
   exactitud cómo se usan los datos (especialmente si usarás WhatsApp Business API).
3. Publica el sitio con GitHub Pages (ver más abajo) y usa la URL de
   `privacy.html` como "Privacy Policy URL" al configurar tu app en
   [Meta for Developers](https://developers.facebook.com/).

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub (puede ser público o privado; para
   GitHub Pages gratuito en cuentas personales, normalmente debe ser público).
2. Sube estos archivos a la raíz del repositorio (rama `main`).
3. Ve a **Settings → Pages**, en "Source" elige la rama `main` y la carpeta `/root`.
4. Guarda. GitHub te dará una URL del tipo:
   `https://<tu-usuario>.github.io/<nombre-del-repo>/`
5. Esa URL (y `/privacy.html` al final) es la que puedes usar en Meta.
