# Recipe Explorer Web App

![React](https://img.shields.io/badge/React-Frontend-blue)
![Vite](https://img.shields.io/badge/Vite-Build%20Tool-purple)
![React Router](https://img.shields.io/badge/React%20Router-Routing-red)
![Material UI](https://img.shields.io/badge/Material%20UI-UI%20Framework-007FFF)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)

[Cardozo Peragallo Carlos Ignacio]

Aplicación web desarrollada en React que permite explorar recetas de cocina.
Cada receta incluye ingredientes, pasos de preparación, tiempo estimado y nivel de dificultad.

La aplicación utiliza Context API para la gestión del estado global y Material UI para una interfaz moderna y responsiva.


## Tech Stack

- React
- Vite
- React Router
- Material UI
- Context API

## Características

- **Listado de recetas**: Visualiza todas las recetas disponibles en un formato de grilla.
- **Detalle de recetas**: Explora información detallada de cada receta, incluyendo ingredientes y pasos.
- **Context API**: Manejo del estado global para compartir datos entre componentes.
- **Material-UI**: Diseño moderno y responsivo utilizando componentes de Material-UI.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/CardozoNacho/ReactTPProgIV.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd ReactTPProgIV
   ```
3. Instala las dependencias:
   ```bash
   npm install
   ```
4. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

## Estructura del Proyecto

- `src/components`: Contiene los componentes reutilizables como tarjetas de recetas y listas.
- `src/contexts`: Manejo del estado global con Context API.
- `src/data`: Datos estáticos como recetas en formato JSON.
- `src/pages`: Páginas principales de la aplicación.
- `public`: Archivos estáticos como imágenes y el archivo `index.html`.

## Screenshots

![Listado de recetas](screenshots/Index.png)
_Página principal_

![Error 404](screenshots/RecetaNoEncontrada.png)
_Error de receta no encontrada_

![Detalle](screenshots/RecetasId.png)
_Detalle completo de la receta_



## Autor

- Cardozo Peragallo Carlos Ignacio
- carloscardozoperagallo@alu.frp.utn.edu.ar
- GitHub: [@CardozoNacho](https://github.com/CardozoNacho)

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor crea un fork del repositorio y envía un pull request con tus cambios.
