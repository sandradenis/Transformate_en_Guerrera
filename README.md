⚔️ ¡Transfórmate en Guerrera! 🛡️

Esta es una aplicación web de una sola página (Single Page Application - SPA) diseñada para que los usuarios puedan subir una foto y transformarla en una versión épica de guerrera utilizando el modelo de inteligencia artificial Gemini-2.5-Flash-Image-Preview.

El proyecto está diseñado para ser desplegado de forma gratuita y sencilla usando GitHub Pages.

1. Requisitos Clave

Para que la aplicación funcione una vez desplegada en GitHub Pages, es OBLIGATORIO obtener y configurar una clave de API:

Google AI API Key: Debes obtener una clave de API de Google AI Studio y reemplazar el marcador de posición en el código fuente de index.html.

⚠️ Configuración de la API Key

En el archivo index.html, debes editar la siguiente línea de JavaScript:

const apiKey = ""; // ¡REEMPLAZAR con tu clave de API REAL!


2. Estructura del Proyecto

El proyecto se compone de un solo archivo, lo que facilita su despliegue:

index.html: Contiene todo el HTML (estructura), Tailwind CSS (estilos y responsividad) y JavaScript (lógica de la aplicación y llamadas a la API de Google).

3. Despliegue en GitHub Pages (Pasos para Publicar)

Sigue estos pasos para que tu aplicación esté disponible en una URL pública:

Paso 3.1: Crear y Configurar el Repositorio

Crea un Nuevo Repositorio: Inicia sesión en GitHub y crea un nuevo repositorio (ej: transformate-en-guerrera). Marca la opción para Inicializar este repositorio con un README.

Crea index.html: Dentro de tu repositorio, haz clic en "Add file" > "Create new file" y nómbralo index.html.

Pega el Código: Pega todo el código de la aplicación (el código HTML completo) en este nuevo archivo.

Inserta la API Key: Antes de confirmar, inserta tu clave de API de Google en el código, tal como se indica en la sección 1.

Confirma: Haz clic en "Commit new file" (Confirmar nuevo archivo).

Paso 3.2: Activar GitHub Pages

Ve a Settings: En tu repositorio, haz clic en la pestaña "Settings" (Configuración).

Ve a Pages: En el menú lateral izquierdo, haz clic en "Pages".

Configura la Fuente:

En "Build and deployment", selecciona Deploy from a branch.

Asegúrate de que Branch esté configurado como main (o master) y que la carpeta sea / (root).

Guarda: Haz clic en "Save".

Paso 3.3: Acceder y Compartir

GitHub tardará unos minutos en construir y desplegar tu sitio.

Una vez finalizado, la URL de tu aplicación se mostrará en la misma página de Settings > Pages (será algo como https://[tu-usuario].github.io/[nombre-del-repositorio]/).

¡Comparte esta URL con quien quieras!
