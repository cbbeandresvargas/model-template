# Plantilla para Portafolio de Modelo

Portafolio moderno construido con **Astro**, **Tailwind CSS** y **TypeScript**.

## 🚀 Tecnologías

- **Astro** `^5.16.0` - Framework web moderno
- **Tailwind CSS** `^3.4.17` - Estilos utility-first
- **TypeScript** - Tipado estático
- **Swiper** `^11.1.14` - Carruseles y sliders
- **PhotoSwipe** `^5.4.4` - Lightbox de galería
- **Masonry** `^4.2.2` - Layout de galería
- **imagesLoaded** `^5.0.0` - Detección de carga de imágenes

## 📦 Instalación

```bash
cd proud-photon
npm install
```

## 🧞 Comandos

```bash
npm run dev      # Servidor de desarrollo (http://localhost:4321)
npm run build    # Build de producción
npm run preview  # Preview del build
```

## 📁 Estructura del Proyecto

```
proud-photon/
├── public/              # Assets estáticos
│   ├── fonts/          # Fuentes Roboto
│   ├── images/         # Imágenes generales
│   ├── image/          # Fotos del portafolio
│   └── sprites.svg     # SVG sprites optimizados
├── src/
│   ├── components/
│   │   ├── layout/     # Componentes de layout
│   │   │   ├── Preloader.astro
│   │   │   └── Sidebar.astro
│   │   ├── sections/   # Secciones de páginas
│   │   │   └── Hero.astro
│   │   └── ui/         # Componentes UI
│   │       ├── Icon.astro
│   │       └── SocialLinks.astro
│   ├── layouts/
│   │   └── MainLayout.astro
│   ├── pages/          # Páginas del sitio
│   │   ├── index.astro
│   │   ├── about.astro
│   │   ├── gallery.astro
│   │   ├── gallery-single.astro
│   │   └── contact.astro
│   ├── scripts/        # JavaScript/TypeScript
│   │   ├── animations.ts
│   │   ├── gallery.ts
│   │   ├── menu.ts
│   │   └── slider.ts
│   └── styles/
│       └── global.css  # Estilos globales + Tailwind
├── astro.config.mjs
├── tailwind.config.mjs
├── tsconfig.json
└── package.json
```

## 🎨 Características

### Navegación
- Menú lateral animado con overlay
- Navegación responsive
- Links a todas las páginas
- Hamburger menu

### Páginas
- **Inicio** (`/`) - Hero slider con 4 slides
- **Sobre Mí** (`/about`) - Biografía y medidas profesionales
- **Galería** (`/gallery`) - 4 álbumes categorizados (30+ fotos)
- **Galería Completa** (`/gallery-single`) - Todas las fotos (38 imágenes)
- **Contacto** (`/contact`) - Información de contacto y redes sociales

### Funcionalidades
- ✅ Slider Hero con Swiper (autoplay, navegación, scrollbar)
- ✅ Galería con Masonry layout responsive
- ✅ Lightbox PhotoSwipe para visualización de imágenes
- ✅ Animaciones de scroll con Intersection Observer
- ✅ Lazy loading nativo de imágenes
- ✅ SVG sprites para iconos optimizados
- ✅ Preloader animado

### Estilos
- Tailwind CSS con tema personalizado
- Colores y tipografía del diseño original
- Animaciones suaves y transiciones
- Diseño completamente responsive

## 🔄 Migración Completada

Este proyecto fue migrado desde HTML estático a Astro, con las siguientes mejoras:

### Reemplazos de Librerías
| Antigua | Nueva | Beneficio |
|---------|-------|-----------|
| jQuery | Vanilla JS | -87KB, mejor performance |
| Swiper (compilado) | swiper@11.1.14 | Actualizado, modular |
| WOW.js | Intersection Observer | Nativo, sin dependencias |
| Masonry (compilado) | masonry-layout@4.2.2 | Actualizado |
| Magnific Popup | photoswipe@5.4.4 | Moderno, mejor UX |
| Blazy | Lazy loading nativo | Nativo del navegador |
| Font Awesome | SVG Sprites | -31KB, optimizado |
| Animate.css | Tailwind + Custom | Personalizado, menor tamaño |

### Optimizaciones
- ✅ CSS migrado a Tailwind (de 30KB a clases utility)
- ✅ SVG sprites (8 iconos en 1 archivo)
- ✅ Fuentes optimizadas con font-display: swap
- ✅ Lazy loading de imágenes
- ✅ Código TypeScript tipado

## 👤 Información de Contacto

- **Teléfono**: +591 77550102
- **Email**: Valentina31arce2004@gmail.com
- **Ubicación**: Cochabamba, Bolivia
- **Instagram**: [@valeinanbi](https://www.instagram.com/valeinanbi)
- **Facebook**: [Valentina Arce](https://www.facebook.com/share/1An2zDbSz7/)
- **TikTok**: [@valeinanbi](https://www.tiktok.com/@valeinanbi)

## 📝 Licencia

© 2024 Valentina Arce. Todos los derechos reservados.
