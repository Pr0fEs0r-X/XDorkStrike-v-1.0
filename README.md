# XDORK STRIKE v 1.0

<p align="center">
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
