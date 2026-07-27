# Áureo 2.0 — PWA instalable

Esta versión convierte Áureo en una aplicación web progresiva para iPhone, Android y escritorio.

## Mejoras incluidas
- Instalación desde la pantalla de inicio.
- Apertura en pantalla completa, sin la barra del navegador.
- Ícono oficial de Áureo.
- Pantalla de inicio para iPhone 13/13 Pro y iPhone de 6.7".
- Funcionamiento sin conexión mediante service worker.
- Indicador de guardado local.
- Aviso cuando el dispositivo queda sin conexión.
- Apariencia automática, clara y oscura.
- Respeto de las áreas seguras del iPhone.
- Manifest y accesos directos de la app.

## Publicación en GitHub Pages
Sube **todos** los archivos y carpetas de este ZIP a la raíz del repositorio:
- index.html
- manifest.webmanifest
- service-worker.js
- icons/
- splash/

No subas únicamente index.html, porque la instalación y el modo sin conexión requieren los demás archivos.

## Instalación en iPhone
1. Abre la URL de Áureo en Safari.
2. Toca el botón Compartir.
3. Selecciona “Agregar a pantalla de inicio”.
4. Toca “Agregar”.

Los datos siguen guardándose localmente en el dispositivo mediante localStorage.
