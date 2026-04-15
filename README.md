# 🛒 Eiser - Ecommerce Web System

Bienvenido al repositorio de **Eiser**, un sistema y plantilla web orientada a la creación de una tienda en línea moderna y con un diseño minimalista.

## 📖 Descripción del Proyecto

Sistema es un proyecto estático que ofrece la estructura completa para un Ecommerce (tienda en línea). Cuenta con la interfaz principal preparada para la visualización de catálogo de productos, carrito de compras, proceso de pago, blogs y un formulario de contacto. Está construido con tecnologías amigables y escalables, ideal para pequeñas y medianas empresas o adaptaciones de proyectos más grandes.

## ✨ Características Principales

*   **Página Principal y Navegación:** Menú dinámico y banners responsivos.
*   **Catálogo de Productos:** Vista completa de categorías y múltiples artículos.
*   **Gestión de Carrito (`cart.html` y `checkout.html`):** Vistas detalladas para el cálculo total, revisión de artículos y pantallas para concretar ventas con formularios de envío.
*   **Blogs Integrados:** Apartados para artículos, permitiendo manejo de marketing y retención de clientes.
*   **Apartado de Contacto:** Formulario completamente maquetado y con lógica incrustada mediante PHP.

## 🚀 Tecnologías Utilizadas

Este proyecto fue desarrollado bajo una arquitectura principalmente "Frontend" aprovechando diversas herramientas:

*   **HTML5 & CSS3:** Estructura y maquetado moderno de todas las páginas de la tienda.
*   **Bootstrap 4:** Framework principal para tener un diseño completamente adaptable a dispositivos móviles (Responsive Web Design).
*   **JavaScript (jQuery & Plugins):** Para animaciones, carruseles de productos (Owl Carousel), Lightbox, menús y utilidades UI interactivas.
*   **Sass (SCSS):** Para la organización modular de los estilos visuales del proyecto.
*   **PHP:** Utilizado para gestionar la peticiones en servidor del formulario interactivo de contacto (`contact_process.php`).

## 🛠️ Cómo ejecutar el proyecto de forma local

Dado que el proyecto se compone principalmente de activos estáticos (HTML/CSS/JS), correrlo en tu computadora es un proceso muy directo:

1. **Clona este repositorio:**
   ```bash
   git clone https://github.com/15aozzz/Sistema.git
   ```
2. **Navega a la carpeta del proyecto:**
   ```bash
   cd Sistema/eiser
   ```
3. **Inicia un Servidor Local (Recomendado)**
   Si bien puedes simplemente abrir el archivo `index.html` con tu navegador dando doble clic, es altamente recomendable usar un servidor de desarrollo local para evitar problemas con la carga estricta de íconos o rutas.

   *Si usas Visual Studio Code:*
   Se recomienda usar la extensión **Live Server**. Simplemente haz clic derecho sobre `index.html` y luego en *Open with Live Server*.

   *Si usas Python (Terminal):*
   ```bash
   python -m http.server 8000
   ```
   *Si tienes PHP instalado (Necesario si quieres probar el formulario de contacto):*
   ```bash
   php -S localhost:8000
   ```
   Luego, ve a tu navegador local en la dirección `http://localhost:8000`.

---
*Desarrollado y estructurado con dedicación.*
