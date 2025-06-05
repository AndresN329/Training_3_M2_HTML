# 🚁 DJI Mini 4 Pro Landing Page

Este proyecto es una **landing page responsive** para el dron DJI Mini 4 Pro, desarrollada como parte de un ejercicio de entrenamiento del **Módulo 2, Semana 3** del curso Be a Coder.

---

## 📌 ¿Por qué hice esta página?

Este trabajo fue realizado para **practicar y consolidar conceptos fundamentales de desarrollo web**, específicamente:

- HTML5 semántico
- Flexbox y Grid Layout
- Diseño responsive con media queries
- Buenas prácticas de organización en CSS
- Efectos visuales y animaciones sencillas

---

## ✅ Requisitos que debía cumplir

De acuerdo al enunciado, la página debía incluir:

1. **Estructura básica con HTML5** usando etiquetas semánticas como `<header>`, `<main>`, `<section>`, `<footer>`, etc.
2. **Diseño flexible con Flexbox** para alinear y distribuir el contenido en el `header` y otras secciones.
3. **Diseño adaptable con CSS Grid** en la sección de servicios/tarjetas.
4. **Adaptabilidad para móviles** mediante media queries.
5. **Buenas prácticas**: código limpio, nombres descriptivos, comentarios útiles y archivo CSS separado.

---

## ✨ ¿Qué aprendí?

Durante este proyecto, aprendí a:

- Estructurar correctamente una página con HTML5 semántico.
- Utilizar **Flexbox** para distribuir elementos horizontalmente (como el logo y la barra de navegación).
- Aplicar **CSS Grid** para organizar tarjetas en una cuadrícula responsive.
- Crear una **sección de video de fondo** con contenido superpuesto.
- Usar **media queries** para adaptar la página a pantallas pequeñas (tablets y móviles).
- Aplicar **transiciones y transformaciones CSS** para mejorar la experiencia visual.
- Comprender propiedades avanzadas como `position`, `z-index`, `object-fit`, `transform: translate()` y más.

---

## 🌐 Sobre la página

Esta landing page está diseñada para promocionar el producto **DJI Mini 4 Pro**.

### Contiene:

- Un **encabezado con logo y navegación**
- Un **video de fondo** en pantalla completa con título y botón de acción
- Una sección **grid con tarjetas informativas e imágenes**
- Un **pie de página** simple
- Diseño adaptado para **móviles y tablets**

---

## 🛠️ Tecnologías utilizadas

- **HTML5** – estructura semántica del contenido.
- **CSS3** – estilos visuales, layout (Flexbox y Grid), responsividad.
- **Media Queries** – adaptación a dispositivos pequeños.
- **Animaciones y transiciones CSS** – interactividad visual sutil.

---

## 🧠 Explicación técnica de algunas propiedades clave

| Propiedad                   | Descripción |
|----------------------------|-------------|
| `position: relative`       | Permite mover el elemento y es referencia para hijos `absolute`. |
| `overflow: hidden`         | Oculta contenido que se desborda del contenedor. |
| `position: absolute`       | Posiciona elementos fuera del flujo normal, según su contenedor padre. |
| `top`, `left`              | Determinan la posición exacta cuando se usa `absolute` o `relative`. |
| `min-width` y `min-height` | Evitan que un elemento se haga más pequeño de lo deseado. |
| `transform: translate()`   | Mueve el elemento desde su propio centro. Ideal para centrar elementos. |
| `object-fit: cover`        | Hace que una imagen o video cubra completamente su contenedor sin deformarse. |
| `z-index`                  | Controla qué elementos están por encima o debajo visualmente. |
| `.wrapper > div`           | Aplica estilos solo a los hijos directos del contenedor `.wrapper`. |

---

## 📂 Estructura del proyecto
📁 proyecto-dji-landing-page/
│
├── index.html # Página principal
├── styles.css # Estilos CSS con media queries y animaciones
└── README.md # Este documento

---

## 📱 Diseño responsive

El sitio se adapta automáticamente a:

- 📺 **Escritorios**: cuadrícula de tarjetas, video de fondo completo.
- 📱 **Tablets**: reorganización vertical del contenido.
- 📱 **Móviles**: reducción de textos, botones y reorganización de tarjetas.

---

## 🎯 Próximos pasos (opcional)

- Agregar efectos de scroll con JavaScript.
- Incluir un formulario de contacto real.
- Mejorar accesibilidad (uso de `alt`, navegación por teclado).
- Publicar la página con GitHub Pages o Netlify.

---

## 👨‍💻 Autor

Desarrollado por **Andrés** como parte del entrenamiento Be a Coder – Módulo 2, Semana 3.

---
