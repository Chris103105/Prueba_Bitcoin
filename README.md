# ₿ Bitcoin Price Tracker (PWA)

Aplicación web progresiva (PWA) ligera y responsiva diseñada para consultar el precio actual de **Bitcoin (BTC)** en tiempo real desde cualquier navegador o dispositivo móvil.

##  Características principales

* **Cotización en tiempo real:** Consulta actualizada del valor de Bitcoin mediante API pública de criptomonedas.
* **Aplicación Web Progresiva (PWA):** Incluye `manifest.json` e íconos adaptativos para instalarla directamente en la pantalla de inicio de Android, iOS o escritorio como si fuera una app nativa.
* **Arquitectura minimalista:** Toda la estructura, estilos y lógica están integrados de forma limpia para una carga instantánea sin dependencias pesadas.
* **Diseño responsivo:** Interfaz optimizada para pantallas móviles y de escritorio.

##  Tecnologías utilizadas

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Estándar Web:** Progressive Web App (`manifest.json`)
* **Consumo de datos:** Fetch API / REST API de precios de criptomonedas

##  Estructura del proyecto

```text
├── index.html             # Estructura principal, estilos y lógica de consulta de precio
├── manifest.json          # Configuración de la PWA (nombre, colores, orientación e íconos)
├── apple-touch-icon.png   # Ícono de acceso directo para dispositivos iOS
├── icon-192.png           # Ícono estándar PWA (192x192 px)
└── icon-512.png           # Ícono de alta resolución PWA (512x512 px)
