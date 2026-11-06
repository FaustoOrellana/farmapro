# FarmaPro - Guía Farmacológica Integral

**FarmaPro** es una Progressive Web App (PWA) de consulta y apoyo académico diseñada para estudiantes, docentes y profesionales del área farmacéutica y médica. Proporciona acceso interactivo y sin conexión a una base clínica estructurada de medicamentos, simuladores de evaluación, fichas de memoria activa y protocolos normativos esenciales.

---

## Características Principales

* **Catálogo Farmacológico Auditado**: Consulta detallada de 200 medicamentos con clasificación ATC, composición, mecanismos de acción, indicaciones clínicas, reacciones adversas (RAM), contraindicaciones e interacciones relevantes.
* **Simulador de Pruebas y Casos Clínicos**: Evaluaciones con retroalimentación inmediata, selección aleatoria de reactivos y ponderación de errores frecuentes.
* **Flashcards 3D Interactivas**: Tarjetas de repaso con rotación bidimensional y tridimensional para el entrenamiento de memoria activa farmacológica.
* **Módulo Normativo y Operativo**: Guías aplicadas sobre semaforización FEFO, cadena de frío (2 °C a 8 °C), almacenamiento en clima cálido (Zona IVb) y manejo de medicamentos de Control Especial (FNE).
* **Capacidades Offline (PWA)**: Implementación de Service Worker para funcionamiento autónomo sin conexión a internet y almacenamiento local seguro mediante `localStorage`.

---

## Tecnologías Utilizadas

* **HTML5 / CSS3 / JavaScript (ES6+)**: Arquitectura cliente nativa sin dependencias pesadas.
* **Tailwind CSS**: Maquetación reactiva optimizada para interfaces móviles y de escritorio.
* **Font Awesome**: Iconografía médica y funcional.
* **PWA & TWA (Trusted Web Activity)**: Manifiesto web estandarizado y soporte para empaquetado nativo en Android.

---

## Estructura del Proyecto

```text
farmasena/
├── .well-known/
│   └── assetlinks.json       # Enlace de verificación Digital Asset Links para Android
├── index.html                # Aplicación principal y vistas interactivas
├── privacy.html              # Política de privacidad obligatoria
├── manifest.webmanifest      # Metadatos del manifiesto PWA
├── sw.js                     # Service Worker y gestión de caché
├── icon-192.png              # Icono para dispositivos móviles (192x192)
├── icon-512.png              # Icono de alta resolución (512x512)
└── README.md                 # Documentación técnica