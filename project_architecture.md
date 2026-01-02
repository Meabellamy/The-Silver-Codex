mi-landing-project/
│
├── .gitignore             # Archivos que Git debe ignorar (ej. node_modules)
├── LICENSE                # Licencia legal del proyecto
├── package.json           # Metadatos del proyecto y scripts de automatización
├── README.md              # Punto de entrada de información del proyecto
├── index.html             # Página principal (Home)
│
├── assets/                # Recursos estáticos (Multimedia)
│   ├── fonts/             # Tipografías locales (.woff2, .ttf)
│   ├── icons/             # Favicons y SVGs sueltos
│   ├── images/            # Imágenes generales (banners, logos)
│   │   └── articles/      # Imágenes específicas para los artículos
│   └── video/             # Videos alojados localmente
│
├── css/                   # Hojas de estilo
│   ├── base/              # Resets, variables CSS (:root) y tipografía base
│   ├── components/        # Estilos específicos (botones, navbar, footer, cards)
│   ├── pages/             # Estilos únicos por página (ej. articles.css)
│   └── main.css           # Archivo principal que importa a los demás (o el compilado)
│
├── js/                    # Lógica de JavaScript (Vanilla)
│   ├── components/        # Lógica reutilizable (ej. slider.js, modal.js)
│   ├── utils/             # Funciones auxiliares (helpers, formatters)
│   └── main.js            # Punto de entrada del JS
│
├── pages/                 # Sub-páginas del sitio
│   ├── about.html
│   ├── contact.html
│   └── articles/          # Carpeta para agrupar los artículos
│       ├── articulo-1.html
│       └── articulo-2.html
│
└── docs/                  # Documentación técnica adicional
    ├── ARCHITECTURE.md    # Explicación técnica de cómo está organizado
    └── STYLEGUIDE.md      # Guía de estilos (colores, uso de fuentes)