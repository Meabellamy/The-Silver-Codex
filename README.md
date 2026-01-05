# Landing Page Project - [Nombre del Proyecto]

Bienvenido al repositorio de **[Nombre del Proyecto]**. Este proyecto consiste en una Landing Page multi-página diseñada para presentar información y artículos multimedia de manera eficiente, rápida y escalable.

El proyecto está construido siguiendo una arquitectura modular y utiliza tecnologías web estándar sin dependencias de frameworks pesados.

## 🚀 Tecnologías Utilizadas

* **HTML5 Semántico:** Estructura clara y accesible.
* **CSS3 (Vanilla):** Uso de Variables CSS (`:root`), Flexbox y Grid Layout. Metodología BEM (Block Element Modifier) para nomenclatura de clases.
* **JavaScript (Vanilla ES6+):** Lógica modular sin librerías externas (No jQuery, No React).

## 🎨 Sistema de Diseño

El proyecto utiliza variables CSS globales definidas en `:root` para mantener consistencia visual:

### Colores Principales
```css
--background-color: #233648    /* Fondo principal oscuro */
--primary-color: #137fec       /* Azul primario */
--light-blue: #3d9df0          /* Azul claro */
--hover-blue: #5caef3          /* Azul hover */
```

### Colores de Texto
```css
--titles-color: #f6f7f8        /* Títulos y encabezados */
--text-color: #101922          /* Texto principal */
--placeholder-color: #8b9aa8   /* Placeholders de inputs */
```

### Colores de Estado
```css
--success-color: #10b981       /* Estados exitosos */
--warning-color: #f59e0b       /* Advertencias */
--error-color: #ef4444         /* Errores */
```

### Colores de UI
```css
--input-background: #e8ecf0    /* Fondo de inputs */
--border-color: #d1dae3        /* Bordes generales */
--accent-purple: #8b5cf6       /* Acento morado */
```

### Tipografía
```css
--my-font: "Google Sans", sans-serif
```

## 📂 Estructura del Proyecto

La organización de directorios sigue una separación clara de responsabilidades:

```text
/
├── assets/          # Imágenes, videos, fuentes y favicon
├── css/             # Estilos divididos en base, componentes y páginas
├── js/              # Lógica JS dividida en módulos y utilidades
├── pages/           # Sub-páginas (Artículos, Contacto, etc.)
├── docs/            # Documentación técnica adicional
└── index.html       # Punto de entrada principal
```