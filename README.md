# Camino Estoico

Website en español construido con Astro. Presenta la filosofía del proyecto, sus etapas simbólicas y una reflexión diaria guardada únicamente en el navegador.

## Desarrollo

Requiere Node.js 22.12 o superior.

```sh
npm ci --cache /workspace/.npm-cache
npm run dev
```

## Producción

```sh
npm run build
npm run preview
```

La web es estática y no requiere credenciales ni servicios externos. La estructura filosófica combina conceptos históricos y una organización moderna del proyecto. Los rangos no representan superioridad entre personas. La reflexión usa localStorage; no hay cuentas ni sincronización.

## Publicación

Para alojamiento estático, usa `npm run build` y publica `dist/`. Para plataformas que requieren un proceso, compila primero y ejecuta `npm start`; escucha en `0.0.0.0` y respeta `PORT` (4321 por defecto). `astro preview` permite servir esta primera versión, pero para producción se recomienda un alojamiento estático.
