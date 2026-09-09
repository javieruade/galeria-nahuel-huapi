# Galería Visual — Paisajes del Parque Nacional Nahuel Huapi

Proyecto desarrollado para la materia **Diseño y Desarrollo Web** en la UADE (Universidad Argentina de la Empresa). Consiste en un sitio web estático estructurado con HTML5 semántico y maquetado con CSS3 (Flexbox y CSS Grid), enfocado en la exhibición y registro fotográfico de paisajes y entornos naturales del Parque Nacional Nahuel Huapi (Bariloche, Río Negro, Argentina).

---

## Características del Proyecto

- **Estructura semántica:** Uso estricto de etiquetas HTML5 (`header`, `nav`, `main`, `section`, `article`, `footer`).
- **Navegación persistente:** Menú superior con posicionamiento fijo (`position: fixed`) que permite la navegación cruzada entre la portada y las 10 vistas individuales.
- **Maquetación fluida y adaptable:**
  - **CSS Grid** en la grilla principal de la portada (`index.html`) mediante columnas flexibles (`repeat(auto-fit, minmax(...))`).
  - **Flexbox** en la barra de navegación y en el diseño de dos columnas (fotografía y ficha descriptiva) de las páginas de detalle (`foto-01.html` a `foto-10.html`).
- **Diseño responsive:** Dimensionamiento relativo (`max-width: 100%`, `auto`, unidades `rem` y porcentajes) para garantizar la correcta visualización en diferentes resoluciones sin desbordes horizontales.
- **Fotografía de autoría propia:** Registro visual capturado en las inmediaciones del lago y senderos del parque.

---

## Estructura del Sitio

```text
/
├── index.html          # Portada con bienvenida y grilla de accesos
├── foto-01.html        # Detalle de vista 01
├── foto-02.html        # Detalle de vista 02
├── foto-03.html        # Detalle de vista 03
├── foto-04.html        # Detalle de vista 04
├── foto-05.html        # Detalle de vista 05
├── foto-06.html        # Detalle de vista 06
├── foto-07.html        # Detalle de vista 07
├── foto-08.html        # Detalle de vista 08
├── foto-09.html        # Detalle de vista 09
├── foto-10.html        # Detalle de vista 10
├── css/
│   └── style.css       # Hoja de estilos compartida por todo el sitio
├── img/
│   ├── banner.jpg      # Fotografía panorámica de bienvenida
│   └── foto-01.jpg ... foto-10.jpg # Fotografías en alta resolución
└── README.md           # Documentación técnica del proyecto
