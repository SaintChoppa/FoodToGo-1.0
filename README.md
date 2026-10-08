# FoodToGo 1.0

Proyecto final de curso - Desarrollo de Software 2024.

FoodToGo es una aplicación web para un restaurante/servicio de comida a domicilio. Permite a los clientes visualizar menús variados (desayunos, almuerzos, hamburguesas, burritos), obtener información del restaurante y conocer su ubicación y horarios de atención.

## 🚀 Características Principales

- **Catálogo de Productos:** Carruseles dinámicos para visualizar categorías de comida.
- **Secciones de Navegación:** Inicio, Servicios, Productos, Menú, Información y Contacto.
- **Diseño Responsivo:** Adaptado a diferentes tamaños de pantalla (Mobile Friendly).
- **Integración con Mapas:** Ubicación del local a través de Google Maps.
- **Despliegue Rápido:** Configurado para ser alojado fácilmente en Firebase Hosting.

## 🛠 Stack Tecnológico

- **HTML5:** Estructura semántica de las páginas.
- **CSS3:** Estilos y maquetación visual (`css/style.css`).
- **JavaScript (Vanilla):** Interactividad y lógica básica (`js/script.js`).
- **Swiper JS:** Biblioteca externa utilizada para implementar carruseles interactivos.
- **Firebase Hosting:** Configuración lista (`firebase.json`) para despliegue en la nube.

## 📂 Estructura del Proyecto

```text
/
├── index.html       # Página principal
├── compras.html     # Página de productos y compras
├── info.html        # Información del restaurante
├── erorr.html       # Página de contacto/servicios
├── Tyc.html         # Términos y condiciones
├── firebase.json    # Configuración de alojamiento en Firebase Hosting
├── css/             # Hojas de estilo
├── js/              # Scripts de JavaScript
└── images/          # Recursos gráficos, imágenes y logos
```

## 💻 Cómo Ejecutar el Proyecto

Dado que el proyecto está desarrollado como un frontend web estático, ejecutarlo localmente es muy directo:

### Opción 1: Ejecución Local Directa
1. Clona o extrae el repositorio en tu máquina.
2. Navega hasta la carpeta raíz del proyecto.
3. Haz doble clic en el archivo `index.html` o ábrelo arrastrándolo a cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).

### Opción 2: Usar un Servidor Local (Recomendado)
Para asegurar que todo (incluyendo los scripts) cargue correctamente, se recomienda usar un servidor local de desarrollo:
- **Usando Visual Studio Code:** Instala la extensión **Live Server** y haz clic en "Go Live" estando en `index.html`.
- **Usando Node.js:** Ejecuta `npx serve` dentro del directorio del proyecto en la terminal.
- **Usando Python:** Ejecuta `python -m http.server 8000` (Python 3) en la terminal, y abre `http://localhost:8000` en tu navegador.

### Opción 3: Despliegue en Firebase (Producción)
El proyecto incluye un archivo `firebase.json` listo para ser publicado:
1. Instala Firebase CLI: `npm install -g firebase-tools`
2. Inicia sesión en Firebase: `firebase login`
3. Selecciona tu proyecto: `firebase use <PROJECT_ID>` (o haz un `firebase init`)
4. Despliega la aplicación en internet: `firebase deploy`

## 👥 Desarrollo y Contribución

Este proyecto fue concebido como un **Proyecto Final de Curso**. Las mejoras al código, refactorización y adición de características como un carrito de compras interactivo o integración con base de datos son bienvenidas.

## 📄 Licencia

Desarrollado para propósitos educativos y académicos.
