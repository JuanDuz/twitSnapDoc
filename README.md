# Manual de Usuario de TwitSnap

Bienvenido al manual de usuario de **TwitSnap**.

Esta aplicación fue desarrollada en Android utilizando **Jetpack Compose** como tecnología para la interfaz de usuario. Se implementaron las arquitecturas **MVVM** y **CLEAN**, con una modularización avanzada de la app que permite:

- Separar los scopes de cada módulo.
- Permitir que los desarrolladores puedan tomar ownerships de módulos específicos.
- Facilitar la escalabilidad hacia microfrontends en repositorios separados.

---

## Contenido
1. [Introducción](#introducción)
2. [Guía de uso](#guía-de-uso)
3. [Cómo ejecutar la app desde Android Studio](#cómo-ejecutar-la-app-desde-android-studio)
4. [Preguntas frecuentes](#preguntas-frecuentes)
5. [Aspectos técnicos](#aspectos-técnicos)

---

## Introducción
**TwitSnap** es una herramienta moderna y dinámica diseñada para que los usuarios puedan compartir contenido, interactuar con otros usuarios y mantenerse actualizados en tiempo real.

## Guía de Uso
1. **Inicio:** Abre la aplicación e inicia sesión con tu cuenta.
2. **Funcionalidades principales:**
   - Publica contenido y compártelo con tus seguidores.
   - Descubre nuevos usuarios, hashtags y tendencias.
   - Interactúa con el contenido de otros usuarios.

---

## Cómo ejecutar la app desde Android Studio
Si eres desarrollador y deseas ejecutar la aplicación en tu entorno local, sigue estos pasos:

### **Requisitos previos**
1. **Instala Android Studio:**
   - Descarga la última versión desde [https://developer.android.com/studio](https://developer.android.com/studio).
2. **Configura el JDK:**
   - Asegúrate de tener instalado el **JDK 11** o superior.
3. **Configura un emulador o un dispositivo físico:**
   - Crea un emulador desde el AVD Manager de Android Studio, o conecta un dispositivo físico con el modo de desarrollador habilitado.

### **Pasos para ejecutar TwitSnap**
1. **Clona el repositorio de TwitSnap:**
   - Usa el siguiente comando en tu terminal:
     ```bash
     git clone git@github.com:The-Psyducks/mobile-android.git
     ```
2. **Abre el proyecto en Android Studio:**
   - Haz clic en **File > Open** y selecciona la carpeta del proyecto clonado.
3. **Selecciona la build variant de prodDebug:**
   - En la sección de build variants de Android studio, seleccionar prodDebug para :app.
4. **Sincroniza el proyecto con Gradle:**
   - Android Studio te pedirá sincronizar. Haz clic en **Sync Now**.
5. **Ejecuta la aplicación:**
   - Haz clic en el botón **Run** (el triángulo verde) en la parte superior derecha.
6. **Selecciona un dispositivo:**
   - Elige un emulador o un dispositivo conectado.
7. ¡Listo! La aplicación se ejecutará en tu dispositivo o emulador.

---

## Aspectos Técnicos
Esta aplicación fue desarrollada con las siguientes tecnologías y prácticas:

- **Jetpack Compose:** Para construir una interfaz moderna, eficiente y declarativa.
- **Arquitectura MVVM y CLEAN:** Separación clara de responsabilidades entre las capas de datos, dominio y presentación.
- **Modularización avanzada:**
  - Permite separar los scopes de cada módulo.
  - Facilita que desarrolladores puedan ser responsables de módulos específicos (ownership).
  - Habilita la posibilidad de escalar la aplicación hacia microfrontends en repositorios separados.
- **Prácticas de desarrollo escalables:** La arquitectura está diseñada para soportar equipos grandes y permitir el crecimiento continuo de la aplicación.

---

¡Gracias por usar **TwitSnap**!
