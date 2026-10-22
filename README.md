# VisualCX para Android

Proyecto inicial de una app Android que abre https://www.visualcx.co dentro de un WebView.

## Cómo generar el APK usando solo el celular

Este ZIP contiene el código fuente, no un APK ya compilado. Para compilar sin computador:

1. En Chrome, abre https://github.com/ y crea/inicia sesión en una cuenta.
2. Crea un repositorio nuevo llamado `VisualCX` (puede ser privado).
3. Descomprime este ZIP en tu teléfono y sube todos los archivos y carpetas al repositorio conservando la estructura. También puedes subir el ZIP y extraerlo localmente antes de subirlo; GitHub no compila un ZIP subido sin extraer.
4. En el repositorio, abre la pestaña **Actions** y selecciona **Build VisualCX APK**.
5. Pulsa **Run workflow** y espera a que termine.
6. Abre la ejecución completada y descarga el artefacto `VisualCX-debug-apk`.
7. Extrae el artefacto ZIP para encontrar `app-debug.apk`, ábrelo e instala si Android lo permite.

## Notas
- Requiere conexión a Internet para mostrar la página.
- Es una compilación de depuración para pruebas, no una versión firmada para publicar en Google Play.
- La web puede usar funciones de navegador que necesiten ajustes extra. Prueba inicio de sesión, enlaces y formularios.
- No se incluye ningún logotipo oficial; Android mostrará el icono predeterminado hasta personalizarlo.
