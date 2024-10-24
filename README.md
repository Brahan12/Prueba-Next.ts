# Mi Aplicación Next.js

Bienvenido a **Mi Aplicación Next.js**, un proyecto que utiliza **Next.js** con **TypeScript** para mostrar y gestionar publicaciones desde una API pública y localStorage. Este proyecto incluye funcionalidad para listar, editar y actualizar publicaciones, tanto desde una API pública como almacenadas localmente.

## Funcionalidades

- **Listar publicaciones**: Muestra publicaciones traídas desde la API de JSONPlaceholder o almacenadas en `localStorage`.
- **Editar publicaciones**: Permite editar publicaciones almacenadas localmente.
- **Guardar publicaciones**: Las publicaciones se pueden guardar en `localStorage` para actualizaciones y persistencia.
- **Responsive Design**: El diseño se adapta a diferentes tamaños de pantalla usando **Tailwind CSS**.
- **Optimización de imágenes**: Las imágenes de las publicaciones se obtienen de la API JSONPlaceholder.
  
## Tecnologías Utilizadas

- **Next.js**: Framework de React para aplicaciones web.
- **TypeScript**: Tipado estático en JavaScript para mayor robustez.
- **Tailwind CSS**: Framework CSS para diseño responsive.
- **JSONPlaceholder**: API de ejemplo utilizada para obtener datos ficticios.
- **localStorage**: Almacenamiento en el navegador para la persistencia de publicaciones.

## Requisitos Previos

Antes de comenzar, asegúrate de tener instalado lo siguiente:

- **Node.js** (versión 12 o superior): [Descargar Node.js](https://nodejs.org/)
- **Git**: [Descargar Git](https://git-scm.com/)

## Instalación

1. **Clona el repositorio** en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/mi-aplicacion-nextjs.git
   cd mi-aplicacion-nextjs

2. **Instala las dependencias del proyecto usando npm**
   
   npm install

## Scripts

    npm run dev: Inicia el servidor de desarrollo.

## Uso de la Aplicación

    1. Página Principal
    En la página principal (/), verás un botón que te redirige a la página de listado de publicaciones. La página está diseñada para ser visualmente atractiva y totalmente responsive.

    2. Listado de Publicaciones
    En la página /listado, se listan todas las publicaciones obtenidas desde la API pública y las que hayas almacenado en localStorage. Cada publicación puede ser editada haciendo clic en el botón "Editar" y eliminar con el botón "Eliminar".

    3. Crear Publicaciones
    En la página /nuevo se puede crear una nueva publicación agregando el titulo, contenido e imagen.

    4. Actualizar Publicaciones en localStorage
    Las publicaciones traídas desde la API se pueden almacenar en localStorage para persistencia local. Esto permite que puedas editar las publicaciones incluso después de recargar la página.

    5. Editar Publicaciones
    En la página /post/[id]/edit, puedes editar publicaciones. Si la publicación proviene de localStorage, puedes editarla y los cambios se guardarán localmente. Las publicaciones de la API no pueden ser actualizadas directamente, pero puedes guardarlas en localStorage y luego editarlas.

    6. Borrar Publicaciones
    En la página se puede eliminar/borrar la publicación creada o existente.


## Diseño Responsive

    La aplicación está diseñada para ser responsive utilizando Tailwind CSS. El contenido se adapta dinámicamente a diferentes tamaños de pantalla, proporcionando una experiencia óptima tanto en dispositivos móviles como en pantallas más grandes.

## Autor

    Este proyecto fue creado por Brahan Andres Acosta Galindo. Puedes contactarme en brahan.acostagal@gmail.com.
# Prueba-Next.ts
