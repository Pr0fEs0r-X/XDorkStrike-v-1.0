# XDORK STRIKE v 1.0
<img width="500" height="400" alt="drokstrike" src="https://github.com/user-attachments/assets/d85eaa5f-d880-4207-8a81-4014c1f3f942" />
<br><br>
<p align="center">
  
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) 
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white) 
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
<br>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen" alt="Status">
  <img src="https://img.shields.io/badge/Version-2.5-yellow" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-blue" alt="License">
  <img src="https://img.shields.io/badge/Platform-Web-lightgrey" alt="Platform">
</p>

---

### Descripción

**DORK_STRIKE** es una herramienta de seguridad web con estética de terminal CRT (phosphor green), diseñada para asistir a investigadores de seguridad y pentesters en la generación masiva de **Google Dorks**.

La aplicación permite introducir un dominio objetivo y generar automáticamente más de 50 consultas de búsqueda avanzadas (dorks) categorizadas y con niveles de severidad. Estas consultas ayudan a identificar archivos expuestos, paneles de administración, información sensible y posibles vectores de vulnerabilidad en el dominio especificado.

---

### Características Principales

- **Estética Terminal CRT**: Diseño inmersivo con efectos de scanlines, brillo fosforescente verde y tipografía monoespaciada.
- **Motor de Dorks Corregido**: Sintaxis optimizada para Google. Uso correcto de paréntesis para operadores lógicos `OR` y filtrado estricto por dominio (`site:`).
- **50+ Plantillas de Búsqueda**: Cobertura amplia de vectores de reconocimiento.
- **Categorización**: Los dorks se clasifican en 5 categorías:
  - `FILES`: Documentos y archivos expuestos (pdf, doc, sql, bak).
  - `ADMIN`: Paneles de login y áreas administrativas.
  - `SENSITIVE`: Archivos con credenciales, claves API y configuraciones.
  - `VULNS`: Posibles puntos de inyección SQL, XSS y errores de depuración.
  - `DIRECTORY`: Directorios abiertos con "Index of".
- **Niveles de Severidad**: Clasificación visual por color (Low, Medium, High, Critical).
- **Ejecución Dual**:
  - Ejecución individual por cada dork.
  - Ejecución masiva de los seleccionados.
- **100% Client-Side**: No requiere backend ni base de datos. Funciona en cualquier navegador moderno.

---

### Instalación y Uso

Al ser una herramienta basada en un único archivo HTML, no requiere instalación compleja.

1.  **Descarga**: Guarda el archivo `index.html` en tu ordenador.
2.  **Ejecución**: Haz doble clic en el archivo para abrirlo en tu navegador predeterminado.
3.  **Operación**:
    - Introduce el dominio objetivo en el campo de texto (ej: `example.com`).
    - Pulsa **Generate** para crear la lista de dorks.
    - Selecciona los dorks deseados o filtra por categoría.
    - Pulsa **RUN** en una tarjeta individual o **Execute Selected** para abrir las búsquedas en Google.

---

### Tecnologías Utilizadas

- **HTML5**: Estructura semántica.
- **Tailwind CSS**: Sistema de diseño utility-first (CDN).
- **Vanilla JavaScript (ES6+)**: Lógica de generación y manipulación del DOM.
- **Fonts**: JetBrains Mono & Share Tech Mono.

---

### ⚠️ Aviso Legal y Ético

> **ADVERTENCIA**: Esta herramienta está diseñada únicamente para fines educativos y de investigación de seguridad autorizada.

El uso de esta herramienta para realizar escaneos no autorizados, acceder a información restringida o violar la privacidad de terceros sin consentimiento explícito es **ilegal**. El desarrollador no se hace responsable del mal uso de este software. Utilízalo siempre sobre activos propios o para los cuales tengas permiso explícito por escrito.

---

### Sobre el Desarrollador

Esta herramienta fue diseñada y programada con el objetivo de ofrecer una interfaz funcional y estéticamente única para la comunidad de ciberseguridad.

**Programador / Developer**:  
- **Nombre**: [Rodolfo Hernández Baz / Pr@fEs0r X]  
- **Rol**: Desarrollador de Seguridad / Frontend Engineer / Hacker / Pentester / Forensic 
- **Contacto**: [Rodolfohbaz@gmail.com / ]  
- **GitHub**: [https://github.com/Pr0fEs0r-X]

*Desarrollado con asistencia de modelos de lenguaje avanzados para la optimización de la sintaxis de dorks y el diseño visual.*

---

### Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.


Aquí tienes una propuesta completa para tu archivo `README.md`. Está formateado con Markdown estándar (como el que se usa en GitHub) e incluye los "badges" (insignias) con los iconos y colores oficiales de cada tecnología.

Solo necesitas reemplazar `NOMBRE_DEL_PROYECTO` y la descripción general por la de tu proyecto.

```markdown
# 🚀 NOMBRE_DEL_PROYECTO

Breve descripción de lo que hace tu proyecto y cuál es su propósito principal.

---

## 🛠️ Tech Stack (Tecnologías Utilizadas)

Este proyecto ha sido construido utilizando tecnologías web modernas y estándares actuales:

<p align="left">
  <!-- HTML5 -->
  <a href="https://developer.mozilla.org/es/docs/Web/HTML" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge"/>
  </a>
  <!-- Tailwind CSS -->
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS Badge"/>
  </a>
  <!-- JavaScript -->
  <a href="https://developer.mozilla.org/es/docs/Web/JavaScript" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript Badge"/>
  </a>
</p>

### 📋 Detalles de Implementación

*   **HTML5:** Estructura semántica.
    *   Uso de etiquetas modernas para una mejor accesibilidad y SEO.
*   **Tailwind CSS:** Sistema de diseño utility-first (CDN).
    *   Estilizado rápido y responsivo directamente en el marcado.
*   **Vanilla JavaScript (ES6+):** Lógica de generación y manipulación del DOM.
    *   Código modular, uso de arrow functions, promesas y manipulación eficiente del DOM sin frameworks pesados.

---

## 🔤 Tipografías

La estética visual del proyecto se apoya en fuentes monoespaciadas modernas para un look técnico y limpio:

*   **Primary Font:** [JetBrains Mono](https://www.jetbrains.com/lp/mono/)
*   **Secondary Font:** [Share Tech Mono](https://fonts.google.com/specimen/Share+Tech+Mono)

---

## ⚙️ Instalación y Uso

1.  Clona el repositorio:
    ```bash
    git clone https://github.com/tu-usuario/tu-proyecto.git
    ```
2.  Abre el archivo `index.html` en tu navegador.
    *   *Nota: Al usar Tailwind via CDN, no requiere pasos de compilación complejos.*

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.
```
