# Colores de tu foto

Pequeña herramienta web para explorar los colores de una imagen y consultar referencias Pantone aproximadas. La foto se procesa localmente en el navegador y no se sube a un servidor.

Abre la app publicada: https://oscurt.github.io/colores-foto/

## Flujo de trabajo

- `main` es la rama principal y contiene la versión publicada.
- Crea una rama nueva por cada cambio, a partir de `main`. Usa nombres descriptivos, por ejemplo `feat/nombre-cambio` o `fix/nombre-error`.
- Haz los cambios y commits en esa rama; no trabajes directamente en `main`.
- Abre un Pull Request (PR) de tu rama hacia `main`, revisa el diff y comprueba que la app sigue funcionando.
- Al aprobarlo, integra el PR en `main`. GitHub Pages publica automáticamente los cambios.
- Elimina la rama de trabajo después de integrar el PR.

## Releases

Usa etiquetas versionadas con SemVer. Para versiones previas a la primera estable, añade el sufijo `-alpha`, `-beta` o `-rc`. Publica el release desde el commit de `main` que se quiere distribuir e incluye un resumen de cambios.

## Nota sobre las referencias de color

Los nombres y códigos Pantone que aparecen en la app son coincidencias visuales aproximadas contra una selección limitada de colores. No son una conversión oficial ni sustituyen una guía Pantone licenciada.
