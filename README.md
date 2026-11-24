# Centro de control de incidencias EJE No Penal · V4.2

Aplicación estática autónoma. No requiere dependencias, servidor, variables de entorno ni compilación.

## Publicar en Vercel
1. Extraer el ZIP y cargar `index.html` y `vercel.json` en la raíz de un repositorio privado de GitHub.
2. En Vercel, seleccionar Add New → Project e importar el repositorio.
3. Elegir Framework Preset: Other. Mantener sin comando de build y sin directorio de salida personalizado.
4. Seleccionar Deploy.

Alternativa con Vercel CLI: ejecutar `npx vercel --prod` desde la carpeta extraída y seguir las instrucciones de autenticación y vinculación.

## Datos
67 incidencias, corte del 24/11/2026. Severidad registrada: 14 críticas, 16 altas, 31 medias y 6 bajas. Filtros, indicadores, matriz de severidad, línea temporal, comparación y exportaciones incluyen este atributo. Los datos y las descripciones se incorporan en `index.html`; no hay actualización automática. Para proteger información institucional, configurar acceso restringido antes de publicar. Un repositorio privado por sí solo no protege un sitio público de Vercel.
