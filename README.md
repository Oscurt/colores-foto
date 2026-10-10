# Colores de tu foto

Pequeña herramienta web para explorar los colores de una imagen y consultar referencias Pantone aproximadas. La foto se procesa localmente en el navegador y no se sube a un servidor.

App publicada: https://oscurt.github.io/colores-foto/

## Flujo de trabajo

- `main` es la rama principal. No se trabaja directamente en ella.
- Crea una rama nueva por cada cambio, a partir de `main`, con un nombre descriptivo como `feat/nombre-cambio`, `fix/nombre-error` o `ci/cambio-deploy`.
- Haz los cambios y commits en esa rama.
- Abre un Pull Request (PR) de tu rama hacia `main`; revisa el diff y comprueba que la app sigue funcionando.
- Integra el PR en `main` y elimina la rama de trabajo después del merge.

## Publicación

GitHub Pages publica únicamente los tags que se publican como Releases. Al integrar un PR en `main`, la web publicada no cambia. Para publicar una versión nueva, crea un Release desde el commit de `main` que quieras publicar; la acción de GitHub Actions despliega ese tag automáticamente. La web siempre muestra el último release publicado que haya terminado de desplegarse.

## Releases

Usa etiquetas versionadas con SemVer. Para versiones previas a la primera estable, añade el sufijo `-alpha`, `-beta` o `-rc` e incluye un resumen de cambios.

## Nota sobre las referencias de color

Los nombres y códigos Pantone que aparecen en la app son coincidencias visuales aproximadas contra una selección limitada de colores. No son una conversión oficial ni sustituyen una guía Pantone licenciada.
