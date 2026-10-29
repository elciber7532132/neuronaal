# NeuroLab Enterprise — Frontend funcional

Frontend independiente construido con React, TypeScript y Vite, siguiendo los diez módulos del Documento Maestro de Desarrollo de Semana 11. No contiene backend ni servicios externos.

## Requisitos
- Node.js 20 o superior recomendado
- npm

## Ejecutar
```bash
npm install
npm run dev
```
Abre la URL que indique Vite, normalmente `http://localhost:5173`.

## Verificar la compilación
```bash
npm run build
npm run preview
```

## Módulos incluidos
1. Inicio / Dashboard
2. Proyectos de IA
3. Fundamentos neuronales
4. Diseñador de arquitecturas
5. Datasets
6. Entrenamientos
7. Evaluación y métricas
8. Registro de modelos
9. Reportes
10. Administración y seguridad

## Acciones funcionales solo en frontend
- Crear, buscar, filtrar, abrir, cambiar estado y eliminar proyectos.
- Consultar fundamentos y conceptos de redes neuronales.
- Elegir familias Feedforward, CNN, RNN y GAN; editar capas, validar arquitectura, guardar borrador y copiar configuración.
- Registrar datasets manualmente o seleccionar archivos locales CSV/JSON/TXT/imagen para guardar sus metadatos; validar, ver detalles, crear versión y eliminar.
- Crear ejecuciones de demostración, cambiar su estado, cancelar ejecuciones activas y consultar métricas de ejemplo.
- Comparar ejecuciones y exportar resultados CSV; imprimir reportes o guardarlos como PDF desde el diálogo del navegador.
- Registrar versiones de modelos, consultar detalles, cambiar estado de revisión, aprobar, duplicar versión o eliminar borradores.
- Invitar usuarios de demostración, cambiar roles, activar/desactivar y eliminar usuarios; guardar límites y preferencias locales.
- Los datos principales y preferencias se guardan en `localStorage` y permanecen en el mismo navegador tras recargar.

## Límites importantes
Este paquete es exclusivamente frontend. No incluye API, servidor, base de datos, autenticación real, seguridad de permisos, almacenamiento remoto, TensorFlow/Keras ni entrenamiento real. Los entrenamientos, métricas y resultados precargados son demostrativos; el selector de archivo lee metadatos localmente y no sube archivos. `localStorage` no es una base de datos ni una medida de seguridad. No guardes información sensible.
