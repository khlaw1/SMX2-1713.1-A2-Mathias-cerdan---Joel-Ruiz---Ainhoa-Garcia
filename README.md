## Proyecto HTML, CSS y JS
# SMX2-1713.1-A2-Mathias-cerdan---Joel-Ruiz---Ainhoa-Garcia
CerdanMathias_SMX2_1773_FASE4_A2
Este es un cambio que estoy realizando.

## Sincronización del repositorio con GitHub

Este proyecto parte del archivo descargable del profesor (SMX2-1713-A2 ArchivoDescargable

### Merge de historiales
Al crear el repositorio en GitHub se generó un commit inicial con un `README.md` en el "nuevo repositorio", mientras que la carpeta local ya tenía su propio historial de commits. Como los dos historiales no tenían ningún commit en común, Git mostró el error y lo que hice fue unirlos.

Para solucionarlo se unieron ambos historiales con un merge usando `--allow-unrelated-histories`, lo que generó el commit "Merge historiales del repositorio". De este modo se conservan los commits locales y el commit inicial del remoto, y el repositorio queda sincronizado.

### Flujo de trabajo
1. `git pull`: traer los últimos cambios del equipo.
2. Modificar los archivos.
3. `git add .`: preparar los cambios.
4. `git commit -m "mensaje"`: guardar los cambios en el historial local.
5. `git push`: subirlos a GitHub.
