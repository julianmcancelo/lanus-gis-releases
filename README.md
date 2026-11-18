<div align="center">
  <h1>Lanús GIS Desktop</h1>
  <p><strong>Plataforma cartográfica nativa para Windows · Trazas, Desvíos y Planos Técnicos Municipales</strong></p>

  <p>
    <a href="https://github.com/julianmcancelo/lanus-gis-releases/releases/latest">
      <img src="https://img.shields.io/github/v/release/julianmcancelo/lanus-gis-releases?label=Última%20Versión&color=0067c0&style=for-the-badge" alt="Última Versión" />
    </a>
    <img src="https://img.shields.io/badge/Plataforma-Windows%2010%2F11%20(x64)-0f294a?style=for-the-badge" alt="Windows" />
    <img src="https://img.shields.io/badge/Auto--Actualizador-Activo-059669?style=for-the-badge" alt="Auto-Updater" />
  </p>
</div>

---

## Descarga

Ve a la sección de **[Releases](https://github.com/julianmcancelo/lanus-gis-releases/releases/latest)** y elige el formato que prefieras:

- **Instalador Windows (`.exe` / `.msi`)**: Recomendado. Incluye **actualización automática** cuando se publica una nueva versión.
- **Versión Portable (`tauri-app.exe`)**: Ejecutable directo sin instalación.

---

## Características Principales

- **Mapa Interactivo de Lanús** (MapLibre GL + OpenStreetMap) con buscador de calles y esquinas.
- **Creador y Editor de Trazas** asistido por OpenStreetMap (OSRM), diferenciación visual entre **Ida** (continua), **Vuelta** (discontinua) y **Desvíos**.
- **Jerarquía Inteligente** (Grupos → Subgrupos → Capas) con Drag & Drop, papelera recuperable e importación de `.geojson` y `.kml`.
- **Generador de Plano Técnico (A4 – A0)** listo para imprimir en PNG o PDF con rótulo municipal y referencias.
- **Control de Acceso y Auditoría** en tiempo real con Firebase (roles, permisos granulares y registro de sesiones).

---

## Requisitos

- **Windows 10 / Windows 11 (64 bits)**
- **WebView2 Runtime** (incluido de forma nativa en Windows 11 y Edge).
- Conexión a internet para sincronización con Firebase y mapas.
