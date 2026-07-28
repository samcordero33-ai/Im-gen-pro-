# ⚡ StudioPic — Optimizador & Editor de Imágenes Client-Side

![Licencia](https://img.shields.io/badge/licencia-MIT-blue.svg)
![Estado](https://img.shields.io/badge/estado-activo-brightgreen.svg)
![Tecnologías](https://img.shields.io/badge/stack-HTML5%20%7C%20TailwindCSS%20%7C%20Vanilla%20JS-purple.svg)
![Privacidad](https://img.shields.io/badge/privacidad-100%25%20Local-emerald.svg)

**StudioPic** es una aplicación web moderna, rápida y completamente autónoma (Single Page Application) diseñada para la mejora, eliminación de fondo y vectorización de imágenes directamente en el navegador web sin depender de servidores o APIs externas.

---

## 📖 Contenido

- [Características Principales](#-características-principales)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Instalación y Uso](#-instalación-y-uso)
- [Despliegue en GitHub Pages](#-despliegue-en-github-pages)
- [Arquitectura e Implementación](#-arquitectura-e-implementación)
- [Privacidad y Seguridad](#-privacidad-y-seguridad)
- [Contribuciones](#-contribuciones)
- [Licencia](#-licencia)

---

## ✨ Características Principales

- 🎨 **Mejora Automática de Imagen:**
  - Ajustes finos de brillo, contraste y saturación en tiempo real.
  - Controles deslizantes e interactivos.

- ✂️ **Eliminación de Fondo (Clear Background):**
  - Algoritmo de filtrado por clave cromática en píxeles.
  - Aislamiento automático de elementos en imágenes con fondos claros/blancos.
  - Previsualización en tiempo real con rejilla de transparencia.

- 📐 **Vectorización & Posterizado:**
  - Cuantización de color paso a paso para crear un acabado estilo ilustración/cel-shading.
  - Definición de bordes y reducción de ruido cromático.

- ⚡ **Procesamiento en Cadena ("Aplicar las 3 funciones"):**
  - Ejecución automatizada de la secuencia completa de optimización en un solo clic.

- 🔒 **100% Privado & Seguro:**
  - Todo el procesamiento de píxeles ocurre de manera local usando el elemento `<canvas>` de HTML5.
  - Ningún archivo se transmite a servidores externos.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 Canvas API:** Manipulación directa de matrices de píxeles (`ImageData`, `ctx.filter`, `ctx.putImageData`).
- **Tailwind CSS (via CDN):** Diseño de interfaz moderno en modo oscuro con soporte responsivo completo.
- **Lucide Icons:** Iconografía limpia e intuitiva.
- **JavaScript (Vanilla ES6+):** Lógica asíncrona client-side sin dependencias de frameworks pesados.

---

## 🚀 Instalación y Uso

### Ejecución Local Directa

1. **Clonar o descargar el repositorio:**
   ```bash
   git clone [https://github.com/tu-usuario/studiopic.git](https://github.com/tu-usuario/studiopic.git)
   cd studiopic
