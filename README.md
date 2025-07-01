# Proyecto BEM - Isabella's Deco

Este proyecto consiste en una landing page diseñada para "Isabella's Deco", una marca dedicada a la decoración de eventos privados. 
La interfaz fue desarrollada respetando la metodología **BEM (Bloques, Elementos, Modificadores)** para la organización de estilos CSS, 
cumpliendo con los requisitos definidos en la consigna del módulo.

---

## 📁 Estructura del proyecto

```
proyecto-bem/
├── assets/
│   └── img
│   └── css
│        └── styles.css
│
└── html/
    └── index.html
```

---

## ✅ Contenido del sitio

- **Header**: logo de la marca + menú de navegación.
- **Sección principal**: artículo con título, párrafo descriptivo e imagen representativa.
- **Galería de imágenes**: cards uniformes de tres eventos (boda, cena privada, cumpleaños).
- **Formulario de contacto**: inputs estilizados con validaciones básicas.
- **Footer**: información de derechos reservados y enlaces a redes sociales.

---

## 🎨 Estilo visual

- Paleta de colores basada en **rose gold y rosa palo**.
- Tipografía: `Playfair Display` para títulos y `Open Sans` para el cuerpo.
- Sombras, bordes redondeados y transiciones suaves.
- Imágenes con `object-fit: cover` y medidas uniformes.
- Animaciones de entrada (`fadeIn`, `slideDown`, `zoomIn`) para mejorar la experiencia visual.

---

## 📐 Metodología BEM aplicada

Ejemplos de clases utilizadas:
- Bloque: `.header`, `.gallery`, `.contact-form`
- Elemento: `.header__logo`, `.nav__item`, `.gallery__card`
- Modificador: `.nav__item--active`

---

## 📱 Responsividad

Se agregaron media queries para adaptar el diseño a:
- Pantallas grandes (PC y laptop)
- Tablets (≤768px)
- Móviles (≤480px)

---

## 📸 Imágenes

Todas las imágenes están integradas en archivos y tienen el mismo tamaño gracias al uso de CSS (`height: 200px` + `object-fit: cover`).

---

## 🧾 Estudiante

Desarrollado por Isabel Palacios

![image](https://github.com/user-attachments/assets/e005e570-4e12-42e8-bee8-bb5077c6dec7)


¡Gracias por visitar Isabella's Deco! 🌸
