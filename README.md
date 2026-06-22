# Feed Automator Core

Pipeline automatizado de generación de imágenes de producto para e-commerce retail usando Python y Google Cloud Run.

## Problema de negocio

La Curacao y Tiendas EFE (Conecta Retail) actualizaban manualmente las imágenes 
de producto cada vez que había cambios de precio por SKU — un proceso que tomaba 
varias horas semanales al equipo de diseño y generaba errores de inconsistencia 
entre el feed de datos y las imágenes publicadas en web.

## Solución

Pipeline desplegado en Google Cloud Run que procesa automáticamente el feed CSV 
de productos, detecta variaciones de precio por SKU y renderiza los nuevos diseños 
gráficos con la información actualizada — sin intervención manual.

## Resultados

- Eliminó el 90% del trabajo manual del equipo de diseño
- Tiempo de actualización: de horas a minutos por ciclo
- Aplicado a SKUs de La Curacao y Tiendas EFE (Conecta Retail)

## Stack tecnológico

- **Python** — procesamiento del feed y renderizado de imágenes
- **Google Cloud Run** — despliegue serverless del pipeline
- **GCP** — infraestructura cloud
- **TypeScript** — generación de URLs de imágenes
