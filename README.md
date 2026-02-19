# Mundo Homeopático - Catálogo Digital 2026

Este es el repositorio oficial de la lista de precios y catálogo digital de **Mundo Homeopático**. La aplicación es una Single Page Application (SPA) robusta diseñada para ofrecer una experiencia rápida, profesional y optimizada para dispositivos móviles.

## Características principales

- **Arquitectura de Archivo Único**: Todo el sistema (HTML, CSS y JS) reside en `index.html` para maximizar la compatibilidad con GitHub Pages y facilitar el mantenimiento.
- **Datos Dinámicos (CMS via Google Sheets)**: Sincronización en tiempo real de precios, navegación, FAQ, distribuidores y configuración SEO a través de Google Sheets.
- **Sistema de Carrito Avanzado**: Permite a los usuarios armar pedidos y enviarlos directamente por WhatsApp a la farmacia o a su distribuidor más cercano.
- **SEO & Schema Markups**: Implementación avanzada de JSON-LD para LocalBusiness, FAQPage, OfferCatalog y VideoObject, maximizando la visibilidad en buscadores.
- **Diseño Premium**: Interfaz moderna construida con Tailwind CSS y variables CSS semánticas (Design Tokens).
- **Optimización de Rendimiento**: Carga diferida de recursos, pre-procesamiento de datos desde caché y uso de proxies para garantizar la conectividad.

## Estructura del Proyecto

- `index.html`: El corazón del proyecto. Contiene la infraestructura, el sistema de diseño, la estructura de interfaz y la lógica de negocio modular.
- `img/`: Directorio de activos visuales y logos de la marca y distribuidores.
- `robots.txt` / `sitemap.xml`: Archivos de configuración para indexación en buscadores.

## Despliegue

El proyecto está diseñado para ser servido directamente mediante **GitHub Pages**. Cualquier cambio subido a la rama `main` se verá reflejado automáticamente en la URL pública.

---
© 2026 Mundo Homeopático - Todos los derechos reservados.

