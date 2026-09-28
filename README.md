# LEX RECOVER — Descargas y actualizaciones

Repositorio **público** solo para las **descargas** de la app **LEX RECOVER**.
El código de la aplicación se mantiene en un repositorio **privado** aparte.

- La app consulta `update.json` para saber si hay una versión nueva.
- El APK se publica en **Releases** con el nombre `app-release.apk`.
- El enlace estable de descarga es:
  `https://github.com/SaveFail/lex-recover-releases/releases/latest/download/app-release.apk`

## Publicar una nueva versión
1. Subir el `versionCode`/`versionName` en el repo de la app y compilar el release firmado.
2. Crear un Release (etiqueta `vX.Y`) adjuntando el APK con el nombre `app-release.apk`.
3. Actualizar `update.json` con el nuevo `versionCode`, `versionName` y notas.

> El APK debe estar firmado con la misma clave que la versión instalada.
