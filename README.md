# 🍜 Restaurante Oishii Ramen - Web Multimedia

> **Tarea 4: Creando contenido multimedia en la web**
> Módulo: Diseño de Interfaces Web (DIW) - DAW
> Curso: 2025/26

Este repositorio contiene el desarrollo de una página web promocional responsiva para un restaurante ("Restaurante Oishii Ramen"), enfocada en la integración, optimización y manipulación de elementos multimedia (Imagen, Audio y Video) utilizando estándares web.

## 🎯 Objetivos del Proyecto

El objetivo principal es cumplir con los Resultados de Aprendizaje, demostrando capacidad para:

- Preparar y optimizar archivos multimedia para la web.
- Integrar contenido multimedia valorando su aportación semántica y estética.
- Diseñar interfaces adaptables sin el uso de frameworks (CSS puro).

## 🛠️ Stack Tecnológico

- **HTML5 Semántico:** Estructura y etiquetas multimedia (`<audio>`, `<video>`, `<picture>`, etc.).
- **CSS3:** Diseño responsivo utilizando **Flexbox** y **CSS Grid**. No se han utilizado frameworks (Bootstrap/Tailwind) según los requisitos.
- **Edición de Imagen:** GIMP / Inkscape (Logotipo vectorial, composiciones, optimización y recorte).
- **Edición de Audio:** Audacity (Mezcla de voz y música, exportación a múltiples formatos).
- **Edición de Video:** AVS Video Editor / OpenShot (Montaje, transiciones y composición). En esta tarea se ha usado otra aplicación (Microsoft Clipchamp).

## 🚀 Despliegue e Instalación

Para visualizar este proyecto localmente en tu ordenador:

1.  **Clona el repositorio:**
    ```bash
    git clone git@github.com:MaribelSR/RestauranteOishiiRamen.git
    ```
2.  **Ejecuta el proyecto:**
    Entra en la carpeta descargada y abre el archivo `index.html` en tu navegador web de preferencia (Chrome, Firefox, Edge).

## 📂 Estructura del Proyecto

La estructura de directorios sigue estrictamente lo solicitado en el enunciado:

```text
├── index.html          # Página principal (Landing Page Multimedia)
├── README.md           # Documentación del repositorio
├── css/
│   └── style.css       # Hoja de estilos principal
├── pagina/
│   └── tarea_4.html    # Informe detallado (Justificaciones, licencias y capturas)
├── imagenes/           # Recursos gráficos (Logos, fondos, composiciones)
├── audios/             # Archivos de audio (mp3, ogg, etc.)
├── videos/             # Archivos de video (mp4, webm, etc.)
└── capturas/           # Evidencias para la documentación
```

---

## 📸 Previsualización

|               Versión Escritorio               |                    Versión Móvil                     |
| :--------------------------------------------: | :--------------------------------------------------: |
| ![Vista PC](/capturas/previsualizacion-pc.png) | ![Vista Movil](/capturas/previsualizacion-movil.png) |

---

✨ Características Implementadas
Este proyecto cumple estrictamente con los requisitos de la Tarea 4, sin utilizar frameworks de CSS (Bootstrap/Tailwind) y priorizando el uso de estándares HTML5.

### 1. Diseño Responsivo (Layout)

- **Versión Escritorio (768px - 1200px):**
  - Contenedor centrado que no excede los 1200px.
  - Implementación de **Flexbox/Grid** para la distribución de la cabecera, contenido y pie.
  - Cabecera con Logotipo y Menú de navegación (Imágenes, Audio, Video, Informe).
- **Versión Móvil (< 768px):**
  - Adaptación de la interfaz para pantallas pequeñas.
  - La barra de navegación se sustituye visualmente por un **icono de hamburguesa** (centrado verticalmente con el logo).
  - Redistribución de elementos en columna.

### 2. Gestión de Imágenes

- **Art Direction (HTML nativo):** Se ha implementado el cambio de imagen según la resolución **sin usar Media Queries de CSS**.
  - _Resolución > 600px:_ Se carga `5_Composicion_1000.xxx`.
  - _Resolución < 600px:_ Se carga automáticamente `6_Composicion_600.xxx` mediante el uso de etiquetas `<picture>` o atributos `srcset`.
- **Logotipo:** Uso de formato vectorial (`.svg`) para máxima nitidez.
- **Optimización:** Todas las imágenes han sido tratadas para mantener un equilibrio entre peso y calidad web.

### 3. Sección de Audio

- **Reproductor:** Incrustado mediante etiqueta `<audio>` de HTML5.
- **Compatibilidad:** Se proporcionan **dos formatos de audio** diferentes para asegurar la reproducción en todos los navegadores (Firefox, Chrome, Edge, Opera).
- **Contenido:** Montaje de audio original (máximo 30s) que combina:
  - Locución de presentación (voz propia).
  - Música de fondo con licencia adecuada.

### 4. Sección de Video

- **Reproductor Personalizado:**
  - Se han **ocultado los controles por defecto** del navegador.
  - Se han implementado **botones personalizados** (JavaScript/HTML) para: Reproducir, Pausar, Control de Volumen y Duración.
  - Inclusión de imagen `poster` inicial.
- **Contenido:** Video tutorial explicativo sobre el uso de capas y lienzos en GIMP (duración < 1 min, peso < 50MB).

### 5. Pie de Página (Footer)

- Dividido en tres secciones semánticas: Imágenes, Audio y Video, indicando el software utilizado en cada una.
- Diseño visual a **dos colores** (mitad y mitad) según lo especificado en el diseño.

---

## 📄 Informe y Documentación (tarea_4.html)

El archivo `pagina/tarea_4.html` actúa como informe técnico del proyecto. En él se incluye:

1.  **Justificaciones:** Explicación de los formatos de archivo elegidos y niveles de compresión/optimización.
2.  **Licencias:** Detalle de las licencias Creative Commons de los recursos utilizados (imágenes de stock, música, etc.).
3.  **Evidencias:**
    - Captura del **Apto del profesor** en el foro.
    - Capturas del proceso de edición en GIMP (propiedades de imagen).
    - Capturas de la línea de tiempo de la edición de video (transiciones y efectos).

## ⚙️ Software Utilizado

Para la realización de los recursos multimedia se han empleado las siguientes herramientas:

- **Edición Web:** Visual Studio Code.
- **Imágenes:** GIMP (Manipulación raster) / Inkscape (Vectorial).
- **Audio:** Audacity (Grabación y mezcla).
- **Video:** Microsoft Clipchamp (Montaje y renderizado).

---

**Nota:** _Este proyecto forma parte del módulo de Diseño de Interfaces Web (DIW) y tiene fines exclusivamente educativos._
