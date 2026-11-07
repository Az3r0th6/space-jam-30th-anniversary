# 🏀🪐 SPACE JAM — 30.º Aniversario (1996 – 2026) | GPU Full-Site Edition

![WebGL2 GPU](https://img.shields.io/badge/GPU_Engine-WebGL2_%2B_GLSL_Shaders-5eff1a?style=for-the-badge&logo=opengl&logoColor=black)
![CSS Architecture](https://img.shields.io/badge/CSS_2026-@layer_%7C_Grid_%7C_Nesting-fff200?style=for-the-badge&logo=css3&logoColor=black)
![Anniversary](https://img.shields.io/badge/Edici%C3%B3n-30.%C2%BA_Aniversario_(1996--2026)-ff6a00?style=for-the-badge)
![Author](https://img.shields.io/badge/Ideado_por-Mart%C3%ADn_Calvo_Ruiz-00f0ff?style=for-the-badge)

> **Conmemorando el 30.º Aniversario del sitio web histórico de Space Jam (1996 – 2026).**  
> Reingeniería integral de UX/UI y gráficos acelerados por hardware (GPU) que preserva los **11 planetas e iconos originales de 1996**, transformando tanto la órbita principal como todas sus subpáginas en una experiencia espacial tridimensional de última generación.

---

## 🚀 Descripción del Proyecto

En noviembre de 1996, el sitio web oficial de **Space Jam** hizo historia utilizando una tabla HTML 3.2 de 5×5 celdas y saltos `<br>` para simular una constelación de planetas en órbita antes de que existiera el estándar CSS1.

Al cumplirse su **30.º Aniversario en 2026**, este proyecto reimagina el sitio completo desde cero aplicando ingeniería web moderna y renderizado en tarjeta gráfica (GPU), sin perder la esencia ni la iconografía original de 1996.

---

## ✨ Características Principales (Ingeniería 2026)

* **🌌 Motor Gráfico WebGL2 + Shaders GLSL en Tiempo Real:**
  * Cálculo matemático por píxel ejecutado directamente en la GPU a 60/120 FPS.
  * **Nebulosa volumétrica fractal (fBm de 5 octavas)** que cambia dinámicamente su espectro de color según el planeta que visitas.
  * **Vórtice de acreción gravitacional** detrás del logotipo central, 3 capas de estrellas en paralaje y **ondas de choque interactivas** al hacer clic.
  * **HUD de Telemetría en Vivo:** Detecta el modelo exacto de la GPU del usuario (`WEBGL_debug_renderer_info`) y monitorea los FPS en tiempo real.
* **🪐 Ecosistema SPA Completo (Los 11 Planetas + Sub-navegación):**
  * Ningún enlace te expulsa al diseño antiguo sin estilo: los **11 sectores planetarios** cuentan con su propia estación 3D, tarjetas holográficas, sub-menús e incluso un visor integrado (`🔌 Archivo 1996 Enmarcado`) para inspeccionar el HTML histórico sin abandonar la interfaz 2026.
  * **Módulos Interactivos Nativos:**
    * 🏀 *Planet B-Ball:* Simulador interactivo de triples **Shooting Hoops**.
    * 🎹 *Lunar Tunes:* Sintetizador espacial en tiempo real con **Web Audio API**.
    * ❓ *The Lineup:* **Trivia Quiz** interactivo sobre la película.
    * 🎨 *Junior Jam:* Pizarra de dibujo láser en **HTML5 Canvas** (*The Coloring Book*).
    * 🗺️ *Site Map & Jump Station:* Matriz interactiva de viaje rápido entre los 11 sectores.
* **🔤 Tipografía Arcade 3D con ADN *Space Jam*:**
  * Sistema tipográfico diferencial basado en `Luckiest Guy`, `Bangers` y `Chakra Petch` con **extrusión sólida en bloque de 8 capas**, inclinación arcade (`skewX(-8deg)`) y la paleta oficial verde lima (`#5eff1a`), amarillo solar (`#fff200`) y naranja (`#ff6a00`).
* **📐 Arquitectura CSS Moderna (2026 Baseline):**
  * Uso de Cascade Layers (`@layer`), CSS Nesting nativo, `color-mix()` y **CSS Grid explícito de 5×4** que reemplaza las tablas y etiquetas `<br>` de 1996 manteniendo las coordenadas orbitales exactas.

---

## 📊 Comparativa Técnica: 1996 vs. 2026

| Dimensión | Sitio Original (1996) | Edición 30.º Aniversario (2026) |
| :--- | :--- | :--- |
| **Motor de Layout** | `<table width="500">` con `colspan` y `rowspan` | `CSS Grid` bidimensional 5×4 + Perspectiva 3D |
| **Fondo Espacial** | Mosaico estático `bg_stars.gif` | Shader GLSL Volumétrico en GPU + Modo Híbrido 1996 |
| **Navegación de Planetas** | Recarga completa en `<frameset>` HTML 3.2 | Enrutador Espacial SPA con transición cromática en GPU |
| **Arquitectura de Estilos** | Atributos inline (`bgcolor`, `<font>`, `<center>`) | `@layer`, CSS Nesting nativo y Custom Properties reactivas |
| **Audio y Juegos** | Archivos `.wav`/`.au` descargables y Shockwave | `Web Audio API` en tiempo real y Canvas 2D/WebGL nativo |

---

## 🛠️ Instalación y Uso Local

El proyecto está diseñado bajo una arquitectura **Zero-Dependencies Single-File** (no requiere `npm install` ni bundlers externos):

1. Clona este repositorio:
   ```bash
   git clone https://github.com/TU-USUARIO/space-jam-30th-anniversary.git
