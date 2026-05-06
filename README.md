# Soluciones Tecnológicas para la Gestión de Datos y Seguridad

Landing page estática para una consultora tecnológica enfocada en PyMEs.

## Estructura

```text
stgds-landing-page/
├── index.html
├── styles.css
├── script.js
└── assets/
    └── logotipos
```

## Cómo editar paquetes y precios

Abre `index.html` y busca la sección:

```html
<section id="paquetes" ...
```

Cada paquete está dentro de:

```html
<article class="price-card">
```

Ahí puedes cambiar:

- Nombre del paquete
- Precio
- Lista de beneficios
- Texto precargado de WhatsApp

## Cómo cambiar enlaces de redes

Busca la sección:

```html
<section id="contacto" ...
```

Cambia los botones de Facebook e Instagram reemplazando `href="#"` por tus enlaces reales y elimina la clase `disabled`.

Ejemplo:

```html
<a class="btn btn-secondary" href="https://facebook.com/tu-pagina" target="_blank" rel="noopener">Facebook</a>
```

## WhatsApp actual

El número configurado es:

```text
+52 56 1046 2212
```

## Recomendación de hosting

Puedes subir esta página a:

- Cloudflare Pages
- Vercel
- Netlify
- GitHub Pages

No requiere base de datos ni backend.


## Branding web

Consulta `BRANDING.md` para ver las versiones optimizadas del logo, favicons y reglas de uso.
