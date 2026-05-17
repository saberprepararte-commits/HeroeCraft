# HeroCraft Pomodoro

App Pomodoro gamificada en HTML, CSS y JavaScript puro. Esta carpeta se puede publicar directamente en GitHub Pages.

## Archivos para subir a GitHub

- `index.html`
- `assets/hero-final-v2-transparent.png`
- `.nojekyll`
- `README.md`

## Publicar con GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube todos los archivos de esta carpeta.
3. En GitHub, entra a `Settings` > `Pages`.
4. En `Build and deployment`, elige `Deploy from a branch`.
5. Selecciona la rama `main` y la carpeta `/root`.
6. Guarda y espera a que GitHub genere el enlace.

## Guardado del progreso

El progreso se guarda localmente en el navegador de cada persona con `localStorage`.

Esto significa:

- No necesita registro.
- No necesita base de datos.
- Cada usuario que abra el enlace tendrá su propio avance en su dispositivo/navegador.
- El progreso permanece mientras el usuario no borre los datos del navegador para ese sitio.
- Si cambia de celular o navegador, puede usar `Exportar` e `Importar` para mover su avance.

No se usa IMEI ni IP. El IMEI no está disponible para apps web normales por privacidad, y la IP cambia según la red.
