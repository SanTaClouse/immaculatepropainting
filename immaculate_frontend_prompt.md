# Prompt: Frontend Prototype — Immaculate Pro Painting LLC

## Contexto del Cliente

**Empresa:** Immaculate Pro Painting LLC  
**Dueño:** Ricardo Torres — Owner / Founder  
**Ubicación:** Seattle, WA (también cubre Bellevue, Redmond, Kirkland)  
**Contacto:** (425) 523-4875 · immaculatepropaintingllc@gmail.com  
**Licencia:** LIC #IMMCPP74B8 — Licensed · Bonded · Insured  
**Sitio actual:** www.immaculatepropainting.com (WordPress, a reemplazar)  
**Servicios:** Interior & Exterior Painting — residencial y comercial

---

## Identidad Visual (extraída de tarjeta de presentación oficial)

La tarjeta es el artefacto de marca más importante del cliente. Define todo el sistema visual:

- **Fondo:** Negro mate profundo (`#0A0A0A` / `#111111`)
- **Acento principal:** Dorado cálido tipo foil (`#B8963E` / `#C9A84C`)
- **Texto:** Blanco puro y variantes grisáceas (`#FFFFFF`, `#CCCCCC`)
- **Logo:** Ancla con una casa en el centro — símbolo de solidez, arraigo, confianza
- **Tipografía de marca:** Serif elegante para "IMMACULATE", sans-serif bold condensada para "PRO PAINTING", espaciado generoso en mayúsculas para textos secundarios
- **Estilo general:** Luxury craftsmanship — como una joyería o una firma de arquitectura de alta gama. NO es una empresa de pintura genérica. Es premium, precisa, con actitud.
- **Tagline visual:** "Licensed · Bonded · Insured · Quality You Can Trust"
- **Tone of voice:** Confianza absoluta. Sin excesos decorativos. Cada elemento justifica su presencia.

---

## Tarea

Crear un **prototipo frontend de una sola página (HTML + CSS + JS)** que simule el homepage completo del nuevo sitio web. Debe ser un artefacto autónomo, sin dependencias externas salvo Google Fonts y librerías CDN si es necesario.

---

## Dirección de Diseño

**Concepto:** *"The Anchor Standard"* — la web debe sentirse como entrar a la oficina de una empresa que no necesita convencer a nadie. La calidad se percibe antes de leer una sola palabra.

**Tono estético:** Luxury Dark — similar a marcas como Rolls-Royce, Bang & Olufsen, o estudios de arquitectura de alta gama. Maximalismo contenido: gran presencia visual, pero sin ruido innecesario.

**Lo que debe ser INOLVIDABLE:** El hero. Cuando el usuario cargue la página debe sentir que está en un sitio diferente a cualquier empresa de pintura que haya visto.

---

## Secciones a Incluir (en orden)

### 1. Navigation Bar (fija, siempre visible)
- Logo: ancla dorada + "IMMACULATE PRO PAINTING" en tipografía serif
- Links: Servicios · Galería · Sobre Nosotros · Reseñas · Contacto
- CTA button dorado: **"Cotización Gratis"**
- Fondo transparente que se vuelve negro sólido al hacer scroll
- En mobile: hamburger menu

### 2. Hero Section
- Fondo: negro profundo con textura sutil (ruido, grain, o patrón geométrico muy tenue)
- Elemento decorativo: ancla dorada grande, semi-transparente, como marca de agua al fondo
- Headline principal en serif grande y elegante:  
  *"We Don't Believe in Good Enough."*
- Subtítulo:  
  *"Premium residential & commercial painting in Seattle, WA. Every brushstroke is a promise."*
- Dos CTAs: botón dorado sólido **"Get a Free Quote"** + botón outline dorado **"View Our Work"**
- Badges de confianza debajo: 🔒 Licensed · 🛡️ Bonded · ✅ Insured · ⭐ 5-Star Rated
- Animación de entrada: staggered fade+slide desde abajo, elegante y suave

### 3. Services Section
Cuatro tarjetas para los servicios principales:
- **Interior Painting** — Smooth, elegant finishes for every room
- **Exterior Painting** — Weather-resistant solutions that last
- **Cabinet Painting** — Precision on every detail
- **Commercial** — Professional results with minimal downtime

Diseño: tarjetas oscuras con borde dorado sutil al hover, ícono minimalista dorado, descripción breve, link "Learn more →"

### 4. Why Choose Us (propuesta de valor)
Tres o cuatro pilares visuales en layout horizontal:
- 🎯 Precision — Measure twice, paint once
- ⏱️ Punctuality — On time, every time
- 💎 Premium Materials — Low-VOC, long-lasting finishes
- 🤝 Guaranteed — Your satisfaction or we come back

Estética: números grandes en dorado + texto conciso. Separador horizontal dorado fino entre sección y sección.

### 5. Before & After Gallery (simulada)
- Slider o grid 2x2 con placeholders visuales estilo "before/after"
- Usar gradientes o placeholders elegantes en lugar de imágenes reales
- Etiquetas "Before" / "After" con tipografía clara
- Filtros por categoría: Interior · Exterior · Cabinets · Commercial

### 6. Testimonials / Reviews
- Estilo Google Reviews: estrellitas doradas, nombre del cliente, barrio de Seattle, texto breve
- Mínimo 3 reseñas inventadas pero verosímiles
- Carrusel o layout de tarjetas con fondo gris oscuro (`#1A1A1A`)

### 7. Contact / CTA Final
- Fondo dorado sólido (única sección con fondo dorado — máximo impacto)
- Headline en negro: *"Ready to Transform Your Space?"*
- Botón negro: **"Schedule a Free Estimate"**
- Datos de contacto visibles: teléfono, email, área de cobertura

### 8. Footer
- Logo + tagline
- Links secundarios: Privacidad · Términos · Sitemap
- Íconos de redes sociales (Facebook, Instagram, Google)
- Copyright: © 2025 Immaculate Pro Painting LLC
- Fondo negro, texto gris claro, detalles dorados

---

## Floating Elements (siempre visibles)
- Botón flotante de llamada 📞 — esquina inferior izquierda
- Botón flotante de WhatsApp/mensaje 💬 — esquina inferior derecha
- Ambos en dorado, con sombra sutil y efecto pulse suave

---

## Especificaciones Técnicas

### Paleta de colores (CSS variables)
```css
--color-bg:        #0A0A0A;
--color-surface:   #141414;
--color-surface-2: #1E1E1E;
--color-gold:      #C9A84C;
--color-gold-light:#E2C47A;
--color-gold-dark: #9A7A32;
--color-white:     #FFFFFF;
--color-text:      #E0E0E0;
--color-muted:     #888888;
--color-border:    rgba(201, 168, 76, 0.2);
```

### Tipografía (Google Fonts)
- **Display / Headlines:** `Cormorant Garamond` — serif elegante, weight 300–700
- **UI / Body:** `Montserrat` — sans-serif limpia, weight 300–600
- **Accents / Labels:** `Montserrat` uppercase + letter-spacing generoso

### Animaciones
- Entrada del hero: `opacity 0→1` + `translateY 30px→0`, staggered con delays de 150ms
- Hover en tarjetas: border dorado, sutil `translateY(-4px)`, `box-shadow` dorado difuso
- Scroll reveal: elementos que aparecen suavemente al entrar en viewport (IntersectionObserver)
- Navbar: transición suave de transparente a `#0A0A0A` con backdrop-blur al hacer scroll
- Floating buttons: `box-shadow` pulsante animado en CSS (`@keyframes pulse`)

### Responsive
- Mobile-first
- Breakpoints: 480px · 768px · 1024px · 1280px
- En mobile: hero ocupa full viewport, nav colapsa a hamburger, grid de servicios en columna única

### Otras consideraciones
- Separadores entre secciones: línea horizontal `1px solid rgba(201,168,76,0.3)` o degradado fino
- Cursor personalizado opcional: punto dorado pequeño al hover sobre elementos interactivos
- Textura de fondo en hero: `background-image` con SVG de ruido o patrón geométrico sutil
- Scroll suave: `scroll-behavior: smooth`
- Sin imágenes externas: usar `linear-gradient` o `background-color` como placeholders para fotos

---

## Criterio de Éxito

El prototipo es exitoso si:

1. Al verlo, nadie diría que es una empresa de pintura genérica
2. La paleta negro/dorado/blanco es consistente en cada sección
3. La tipografía Cormorant + Montserrat se siente lujosa, no pesada
4. El hero genera impacto en los primeros 3 segundos
5. Las animaciones se sienten naturales, no llamativas
6. Es 100% funcional en mobile
7. Los CTAs dorados están siempre visibles y accesibles
8. La sección final con fondo dorado cierra el recorrido con fuerza

---

## Referencia de Marca

> *"We are not your average painting company. Every project is an opportunity to set a new standard of excellence."*  
> — Immaculate Pro Painting LLC

La web debe hacer sentir eso desde el primer pixel.
