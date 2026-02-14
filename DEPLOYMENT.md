# Tiempo de Despliegue de GitHub Pages

## ¿Cuánto tarda en desplegarse el sitio después de hacer push?

Según los datos de los últimos despliegues de este repositorio:

### Tiempos Observados

- **Inicio del despliegue**: Típicamente comienza entre **5-10 segundos** después del push
- **Duración del despliegue**: Entre **40-50 segundos** en completarse
- **Tiempo total**: Aproximadamente **1 minuto** desde que haces push hasta que el sitio está actualizado

### Ejemplo Reciente

El último despliegue (2026-02-05):
- Push realizado: 08:17:04 UTC
- Despliegue iniciado: 08:17:09 UTC (5 segundos después)
- Despliegue completado: 08:17:55 UTC (46 segundos total)

## Cómo Verificar el Estado del Despliegue

1. **Ver el estado en tiempo real**:
   - Ve a: https://github.com/Perifulles/MyPortFolio/actions
   - Busca el workflow "pages build and deployment"
   - Verás el estado actual (en progreso, completado, fallido)

2. **Badge de estado**:
   Puedes añadir un badge al README.md para ver el estado de un vistazo:
   ```markdown
   ![GitHub Pages](https://github.com/Perifulles/MyPortFolio/actions/workflows/pages/pages-build-deployment/badge.svg)
   ```

## Tu Sitio Web

- **URL**: https://perifulles.es (según tu archivo CNAME)
- **URL alternativa**: https://perifulles.github.io/MyPortFolio/

## Factores que Pueden Afectar el Tiempo

- Tamaño del sitio web
- Tráfico actual de GitHub
- Configuración de caché del navegador (puede mostrar versión antigua)

### Consejo

Si no ves los cambios inmediatamente después del despliegue:
1. Espera 1-2 minutos adicionales
2. Limpia la caché del navegador (Ctrl + F5 o Cmd + Shift + R)
3. Prueba en modo incógnito/privado del navegador
