# El Rayo de la Construcción — Maestro Jaime

Sitio web estático para **Trabajos de Construcción y Terminaciones en General J.G** ("El Rayo de la Construcción"), del Maestro Jaime. Combarbalá, Región de Coquimbo, Chile.

## Contacto del negocio

- **Maestro Jaime**
- WhatsApp / Teléfono: [+56 9 4080 6403](https://wa.me/56940806403)
- Correo: [albalina494@gmail.com](mailto:albalina494@gmail.com)
- Zona: Combarbalá y alrededores, Región de Coquimbo

## Servicios

Piso flotante · Cerámica · Radier · Puertas y ventanales · Forrados · Pintura · Techumbre · Encielado (con o sin viga) · Portones · Quinchos · Fosa séptica · Cierre perimetral.

## Estructura

```
.
├── index.html          # Sitio completo (HTML + CSS + JS en un archivo)
├── assets/
│   └── book/           # Fotos del trabajo del Maestro Jaime
└── README.md
```

Todo el sitio es **HTML/CSS/JS estático** — no requiere build, ni framework, ni servidor. Se puede abrir el `index.html` directamente en cualquier navegador, o servir desde GitHub Pages, Netlify, Vercel, Cloudflare Pages, o cualquier hosting estático.

## Cómo desplegar en GitHub Pages

1. Cree un repositorio en GitHub (por ejemplo `el-rayo-de-la-construccion`).
2. Suba todos los archivos de este proyecto:
   ```bash
   git init
   git add .
   git commit -m "Sitio inicial — El Rayo de la Construcción"
   git branch -M main
   git remote add origin https://github.com/USUARIO/el-rayo-de-la-construccion.git
   git push -u origin main
   ```
3. En el repo, ir a **Settings → Pages** y elegir Source: `Deploy from a branch`, Branch: `main`, carpeta: `/ (root)`. Guardar.
4. En unos minutos, el sitio estará en `https://USUARIO.github.io/el-rayo-de-la-construccion/`.

## Personalización rápida

Todos los datos editables están en `index.html`:

- **Datos de contacto** — busque `+56 9 4080 6403` y `albalina494@gmail.com` para reemplazarlos.
- **Servicios** — están en el array `SERVICIOS` dentro del `<script>` al final del archivo. Cada servicio tiene `t` (título), `img` (foto) y `d` (descripción).
- **Galería del Book** — array `BOOK` en el mismo `<script>`. Para agregar fotos: copie la imagen a `assets/book/` y agréguela al array.
- **Zonas de cobertura** — sección `<div class="areas">` en la sección "ZONA". Agregue/elimine `<span>` según necesite.

## Tecnología

- HTML5 + CSS3 (sin frameworks)
- JavaScript vanilla
- Google Fonts: Oswald, Source Sans 3, Bebas Neue
- Diseño 100% responsivo (mobile-first)
- Lightbox de galería incluido
- Botón flotante de WhatsApp con animación de pulso

## Licencia

Contenido y fotografías: © Jaime — Trabajos de Construcción y Terminaciones J.G. Todos los derechos reservados.
