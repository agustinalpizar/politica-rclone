# Política de privacidad: rclone (uso personal)

Esta política describe cómo la aplicación OAuth «rclone» (proyecto `rclone-drive` en Google Cloud) usa los datos de Google de su titular.

## Uso
La aplicación se usa solo en el equipo personal del titular de la cuenta, para montar su Google Drive como una unidad local de Windows. No es un servicio para terceros.

## Datos a los que accede
Únicamente los archivos y carpetas de Google Drive que el titular decide ver o modificar desde su equipo, mediante el permiso `https://www.googleapis.com/auth/drive`.

## Dónde se guardan los datos
- El token de acceso se guarda solo en el equipo del titular, en el archivo de configuración de rclone.
- Los archivos abiertos se guardan temporalmente en una caché en el disco local del titular, con límite de tamaño.
- El proyecto no tiene servidores propios y no recibe ni almacena datos del usuario.

## Compartir y venta de datos
No se comparten, venden, transfieren ni usan datos con fines publicitarios. No se envían datos a terceros.

## Revocar el acceso
El titular puede revocar el acceso en cualquier momento desde https://myaccount.google.com/permissions, o eliminando el remoto de rclone.

## Cambios y contacto
Esta política puede actualizarse en este mismo repositorio. Para preguntas, abre un issue en este repositorio.

Última actualización: 2026-11-23.
