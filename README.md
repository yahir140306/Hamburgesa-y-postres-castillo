# Hamburguesas Castillo - Sitio Web

Sitio web para el negocio de hamburguesas y postres "Castillo", desarrollado con Astro y Tailwind CSS.

## 🚀 Características

- ⚡️ Astro 5 - Framework ultrarrápido
- 🎨 Tailwind CSS v4 - Estilos modernos y responsivos
- 📱 Diseño mobile-first
- 🛒 Carrito de compra
- 💬 Integración con WhatsApp

## 📁 Estructura del Proyecto

```
├── public/
│   ├── menu-screenshot.png
│   └── carrito-screenshot.png
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   └── BottomNav.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro      # Página del menú
│   │   └── carrito.astro    # Página del carrito
│   └── styles/
│       └── global.css
└── package.json
```

## 🛠️ Comandos

| Comando           | Acción                                               |
| :---------------- | :--------------------------------------------------- |
| `npm install`     | Instala las dependencias                             |
| `npm run dev`     | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build`   | Construye el sitio para producción en `./dist/`      |
| `npm run preview` | Vista previa de la construcción local                |

## 🎨 Paleta de Colores

- **Primary**: `#F25C24` (Naranja)
- **Primary Dark**: `#D94A15`
- **Secondary Aqua**: `#4FD1C5` (Aqua/Verde para postres)
- **Background Light**: `#FDFBF7`
- **Background Dark**: `#1A1A1A`

## 📱 Páginas

### Menú Principal (`/`)

- Hero con imagen destacada
- Tarjetas de información (horarios, envío, pagos)
- Categorías de productos
- Hamburguesas con imágenes
- Postres y bebidas
- Footer con información de contacto

### Carrito (`/carrito`)

- Lista de productos seleccionados
- Contador de cantidades
- Campo de notas adicionales
- Resumen de precios
- Botón para ordenar por WhatsApp

## 📞 Contacto

- **WhatsApp**: 55 1174 0626 / 55 3972 7686
- **Horario**: Jueves a Domingo, 6:00 PM - 11:00 PM
- **Envío**: ¡Gratis!

## 🔧 Tecnologías Utilizadas

- [Astro](https://astro.build)
- [Tailwind CSS](https://tailwindcss.com)
- [Google Fonts - Poppins](https://fonts.google.com/specimen/Poppins)
- [Material Icons](https://fonts.google.com/icons)

## 📝 Notas de Desarrollo

El proyecto fue convertido desde HTML estático a Astro con las siguientes mejoras:

- Componentes reutilizables (Header, BottomNav)
- Variables CSS personalizadas
- TypeScript para type-safety
- Estructura modular y mantenible
- Optimización de imágenes automática por Astro
# Hamburgesa-y-postres-castillo
