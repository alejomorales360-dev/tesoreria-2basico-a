# Tesorería 2° Básico A · 2026

App de registro de pagos de cuotas y gastos del curso, conectada a
Google Sheets mediante Google Apps Script.

- `index.html` — la app (frontend). Se publica online con GitHub Pages.
- `gas/Code.gs` — el backend de Google Apps Script.
- `gas/README.md` — cómo instalar/redesplegar el backend en tu Google Sheet.

## Publicación (GitHub Pages)

Este repo se publica automáticamente en:

```
https://alejomorales360-dev.github.io/tesoreria-2basico-a/
```

Cada vez que se hace push a `main`, GitHub Pages actualiza el sitio solo.

## Configurar la conexión a Google Sheets

Abre `index.html` y busca la constante `GAS_URL` (dentro de la
"ZONA DE CONFIGURACIÓN" del `<script>`). Debe apuntar a la URL `/exec`
de tu implementación de Apps Script. Ver `gas/README.md` para el detalle
de cómo desplegar/actualizar el backend.
