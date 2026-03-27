# Google-Auth App

Aplicación sencilla de Android con dos pantallas principales:
1. **Pantalla de Inicio de Sesión**: Permite al usuario autenticarse utilizando su cuenta de Google.
2. **Pantalla de Perfil**: Muestra la información del usuario logueado (Nombre y Foto de perfil).

## Tecnologías Utilizadas
- **Jetpack Compose**: Para la interfaz de usuario.
- **Firebase Auth**: Para gestionar la autenticación.
- **Google Sign-In**: Como proveedor de identidad.

## Configuración Necesaria
Para que el proyecto funcione localmente, se deben de añadir los siguientes archivos (omitidos por seguridad):

1. **`app/google-services.json`**: Descargar desde la consola de Firebase.
2. **`secrets.properties`**: Crear este archivo en la raíz del proyecto y añadir el ID de cliente:
