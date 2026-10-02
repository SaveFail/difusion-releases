# Difusión — Descargas y actualizaciones

Repositorio **público** para las **descargas** y **actualizaciones** de la app
**Difusión**. El código fuente se publica aparte en
[`SaveFail/difusion`](https://github.com/SaveFail/difusion).

- La app consulta la **última Release** (API de GitHub) y la compara con la
  versión instalada.
- El APK se publica en **Releases** con el nombre **`difusion.apk`**.
- Enlace estable de descarga:

  `https://github.com/SaveFail/difusion-releases/releases/latest/download/difusion.apk`

## Publicar una nueva versión
1. Subir `versionCode`/`versionName` en el repo de la app y compilar el release firmado.
2. Crear un Release con etiqueta `vX.Y` adjuntando el APK (`difusion.apk`).

> El APK debe estar firmado con la misma clave que la versión instalada.
