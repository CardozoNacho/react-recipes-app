# Recipe Explorer | React, React Router y Material UI

Proyecto académico individual de Carlos Ignacio Cardozo Peragallo. Frontend para explorar recetas desde un JSON local y consultar ingredientes y preparación.

## Implementación

- React 19, React Router 7, Material UI 7 y Vite 5 según `package.json`.
- Context API para recetas y estado de carga.
- Rutas `/`, `/recetas` y `/recetas/:id`.
- Mensaje para un id de receta inexistente.
- Tema claro/oscuro guardado en `localStorage`.

La carga se simula con un temporizador de un segundo; no consume una API externa. El mensaje de receta inexistente no constituye una página HTTP 404 general.

## Ejecución

Usar Node compatible con las dependencias del lockfile.

```bash
git clone https://github.com/CardozoNacho/react-recipes-app.git
cd react-recipes-app
npm ci
npm run dev
```

Abrir la URL indicada por Vite. `npm run build` genera el bundle y `npm run preview` lo sirve localmente. No hay script de pruebas automatizadas.

## Estructura

`src/components/`: componentes; `src/contexts/`: estado; `src/data/recetas.json`: datos; `src/pages/`: pantallas; `src/theme.js`: tema. `index.html` está en la raíz.

## Capturas

![Listado](screenshots/Index.PNG)
![Receta inexistente](screenshots/RecetaNoEncontrada.PNG)
![Detalle](screenshots/RecetasId.PNG)
