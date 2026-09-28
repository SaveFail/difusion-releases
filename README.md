# LEX RECOVER — Descargas y actualizaciones

Repositorio **público** solo para las **descargas** de la app **LEX RECOVER**.
El código de la aplicación se mantiene en un repositorio **privado** aparte.

- La app consulta la **última Release** (API de GitHub) y la compara con la
  versión instalada.
- El APK se publica en **Releases** con el nombre **`app-release.apk`**.
- Enlace estable de descarga:
  `https://github.com/SaveFail/lex-recover-releases/releases/latest/download/app-release.apk`

## Publicar una nueva versión
1. Subir `versionCode`/`versionName` en el repo de la app y compilar el release firmado.
2. Crear un Release con etiqueta `vX.Y` adjuntando el APK con el nombre `app-release.apk`.

> El APK debe estar firmado con la misma clave que la versión instalada.
