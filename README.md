# 🌿 RECOLECTA-RD - Versión Mejorada

Plataforma completa de gestión de residuos en la República Dominicana con mejoras significativas.

## ✨ Características Mejoradas

✅ **32 Ciudades de RD** - Todas las provincias incluidas con coordenadas precisas
✅ **Rotación Automática de Fondos** - 4 imágenes que cambian cada 5 segundos
✅ **Mapa Interactivo** - Ubicación de todas las ciudades con marcadores
✅ **Sistema de Reportes** - Registro de problemáticas ambientales
✅ **JavaScript Separado** - Código modular en archivos .js
✅ **Almacenamiento Local** - Los reportes se guardan en localStorage
✅ **Interfaz Responsiva** - Funciona en móvil, tablet y desktop

## 📁 Estructura de Carpetas

```
recolecta-rd-mejorado/
├── index.html
├── style.css
├── js/
│   ├── config.js
│   ├── background-slider.js
│   ├── map.js
│   ├── reports.js
│   ├── ui-interactions.js
│   └── main.js
└── images/
    ├── bg1.jpg (Botella plástica)
    ├── bg2.jpg (Planta en manos)
    ├── bg3.jpg (Tierra verde)
    └── bg4.jpg (Contaminación)
```

## 🖼️ Instrucciones de Imágenes

### Paso 1: Descarga las 4 imágenes
Descarga estas imágenes de alta resolución:
- **bg1.jpg**: Botella de plástico en tierra (contaminación)
- **bg2.jpg**: Planta en manos (cuidado)
- **bg3.jpg**: Planeta verde en manos (sustentabilidad)
- **bg4.jpg**: Contaminación marina con plástico

### Paso 2: Crea la carpeta `images/`
En la raíz del proyecto, crea una carpeta llamada `images`

### Paso 3: Guarda las imágenes
Coloca las 4 imágenes descargadas en la carpeta `/images/` con estos nombres exactos:
- `bg1.jpg`
- `bg2.jpg`
- `bg3.jpg`
- `bg4.jpg`

### Paso 4: Optimiza las imágenes (IMPORTANTE)
**Recomendaciones de tamaño:**
- Ancho mínimo: 1600px
- Alto mínimo: 900px
- Formato: JPG o PNG
- Tamaño máximo: 500KB por imagen

### Cómo obtener las imágenes:

**Opción 1: Unsplash (Gratis, Alta Calidad)**
1. Ve a https://unsplash.com
2. Busca:
   - "plastic pollution beach" (bg1)
   - "hands holding plant" (bg2)
   - "earth green world" (bg3)
   - "ocean plastic pollution" (bg4)
3. Descarga en tamaño "3x" o "4x"
4. Renombra según corresponda

**Opción 2: Pexels (Gratis, Buena Calidad)**
Ve a https://www.pexels.com y busca términos similares

**Opción 3: Pixabay (Gratis)**
Ve a https://pixabay.com y busca "pollution", "nature", "environment"

## 🚀 Instalación y Uso

### Paso 1: Descargar/Clonar
```bash
git clone https://github.com/josegilrafael07-wq/recolecta-rd-mejorado.git
cd recolecta-rd-mejorado
```

### Paso 2: Agregar imágenes
Sigue las instrucciones de arriba para agregar las 4 imágenes en `/images/`

### Paso 3: Abrir en el navegador
Simplemente abre `index.html` en tu navegador favorito

## 📋 Características Principales

### 1. Rotación de Fondos (5 segundos)
- Las 4 imágenes cambiarán automáticamente cada 5 segundos
- Transición suave con efecto blur
- Se pausa si cambias de pestaña

### 2. Mapa Interactivo
- Todas las 32 ciudades de RD
- Click en marcadores para ver información
- Zoom y paneo disponible

### 3. Sistema de Reportes
- Agrega reportes de problemáticas ambientales
- Filtra por ciudad
- Los reportes se guardan automáticamente en localStorage
- Visualiza todos los reportes creados

### 4. Servicios
- Solicitar recolección
- Ver centros de acopio
- Coordinar brigadas de limpieza

## 🏗️ Estructura de Archivos JS

- **config.js**: Configuración central (ciudades, URLs, mensajes)
- **background-slider.js**: Lógica de rotación de fondos
- **map.js**: Inicialización y control del mapa Leaflet
- **reports.js**: Sistema completo de reportes ambientales
- **ui-interactions.js**: Manejo de eventos y interactividad
- **main.js**: Inicialización principal

## 📱 Compatibilidad

✅ Chrome/Edge
✅ Firefox
✅ Safari
✅ Navegadores móviles (iOS Safari, Chrome Mobile)

## 🔧 Personalización

Todas las configuraciones están centralizadas en `js/config.js`:
- Cambiar intervalo de rotación de fondos
- Modificar colores
- Agregar/editar ciudades
- Cambiar mensajes

## 📞 Contacto

Email: recolectard07@gmail.com
Teléfono: (809) 880-3436

## © 2025
RECOLECTA-RD - Todos los derechos reservados.
