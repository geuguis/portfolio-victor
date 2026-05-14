#  Technical Demo Portfolio

Este repositorio contiene una landing page de alto impacto visual orientada a la estética cyberpunk y HUD industrial. El proyecto funciona como una demostración técnica de integración de gráficos avanzados en entornos web estándar.

## Especificaciones Tecnicas

### Visuales y Renderizado
*   **WebGL Background:** Fondo dinámico basado en Shaders (GLSL) reactivo a la posición del cursor y eventos de clic.
*   **HUD Interface:** Sistema de información en tiempo real con reloj sincronizado, coordenadas y estados de sistema.
*   **Efectos CSS:** Implementación de Glassmorphism, animaciones de escaneo CRT y efectos de iluminación dinámica (Glow Cards) mediante variables CSS.

### Optimización y Rendimiento
*   **Cursor Engine:** Sistema de seguimiento de puntero optimizado mediante requestAnimationFrame para reducir el input lag.
*   **Intersection Observer:** Control de animaciones de entrada y barras de progreso activadas solo cuando son visibles en el viewport.
*   **DPR Scaling:** El motor de renderizado WebGL incluye un límite de Device Pixel Ratio para garantizar fluidez en pantallas de alta densidad sin sobrecargar la GPU.

## Stack Tecnologico
*   HTML5 Semántico
*   CSS3 (Custom Properties, Grid, Flexbox)
*   Vanilla JavaScript (ES6+)
*   GLSL (WebGL Shaders)

## Estructura del Proyecto
*   **Hero Section:** Terminal interactivo con formato JSON.
*   **About:** Sistema de visualización de competencias técnicas.
*   **Skills:** Paneles de aptitudes con cortes geométricos y efectos de luz.
*   **Education:** Tarjetas de formación con estados de competencia adicionales.

## Instalacion y Uso
Al ser una demo técnica basada en estándares puros, no requiere dependencias.
1. Clonar el repositorio.
2. Ejecutar index.html en cualquier navegador moderno con soporte WebGL.

---
*Hecho por [geuguis](https://github.com/geuguis)
