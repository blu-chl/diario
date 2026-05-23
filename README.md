# mi diario

Diario personal con múltiples usuarios, fotos y personalización. Una sola página HTML, sin servidor ni dependencias externas.

## Cómo publicar en GitHub Pages

1. Crear un repositorio en GitHub (puede llamarse `diario` o cualquier nombre)
2. Subir el archivo `index.html` a la rama `main`
3. Ir a **Settings → Pages → Branch: main → Save**
4. En 1-2 minutos estará disponible en: `https://TU_USUARIO.github.io/NOMBRE_REPO`

## Características

- **Pantalla de selección de usuario** al estilo Windows 7
- **Múltiples usuarios** con nombre, ícono emoji o foto de perfil
- **Contraseña** por usuario (hasheada, no se guarda en texto plano)
- **Fotos en las entradas** — se pueden subir imágenes con texto/pie de foto debajo
- **6 fuentes tipográficas** — Lora, Playfair, Crimson, Fraunces, Mono, Sans
- **10 paletas de color** — cream, chalk, dusk, forest, rose, slate, sand, night, blush, mint
- Tamaño de texto ajustable
- Preferencias de estilo guardadas por usuario
- Descargar entrada del día como `.txt`
- Exportar todo el diario como `.txt`

## Almacenamiento

Todo se guarda en `localStorage` del navegador.
- Las entradas de cada usuario son independientes
- Las fotos se guardan como base64 en localStorage (pueden ocupar espacio)
- Si quieres acceso desde otros dispositivos, usa **Exportar todo** y guarda en Google Drive

## Estructura

```
diario/
└── index.html   ← todo el app en un solo archivo
```
