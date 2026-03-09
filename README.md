# Coberturas Parqué-Tarima — PWA

Guía de coberturas de parqué y tarima para reparadores colaboradores.

## Estructura de archivos

```
/
├── index.html          ← App principal
├── manifest.json       ← Manifiesto PWA
├── sw.js               ← Service Worker (funciona offline)
├── favicon.ico         ← Favicon multi-tamaño
└── icons/
    ├── icon-16.png
    ├── icon-32.png
    ├── icon-48.png
    ├── icon-72.png
    ├── icon-96.png
    ├── icon-120.png
    ├── icon-128.png
    ├── icon-144.png
    ├── icon-152.png
    ├── icon-167.png
    ├── icon-180.png
    ├── icon-192.png
    ├── icon-256.png
    ├── icon-384.png
    ├── icon-512.png
    └── apple-touch-icon.png
```

## Despliegue en GitHub Pages

1. Sube todos estos archivos a un repositorio de GitHub (respetando la estructura de carpetas).
2. Ve a **Settings → Pages** → Source: `main` branch, carpeta `/ (root)`.
3. GitHub publicará la app en `https://<usuario>.github.io/<repositorio>/`.

## Instalación como app

| Plataforma | Pasos |
|---|---|
| **Android (Chrome)** | Abre la URL → menú ⋮ → "Añadir a pantalla de inicio" |
| **iOS (Safari)** | Abre la URL → botón compartir □↑ → "Añadir a pantalla de inicio" |
| **PC (Chrome / Edge)** | Abre la URL → icono ⊕ en la barra de direcciones → "Instalar" |

La app funciona **sin conexión** después de la primera carga.
