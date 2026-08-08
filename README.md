# Gestión Comercial Biogreen

Dashboard interno de seguimiento diario de ventas y metas.

**Ver dashboard en vivo:** https://comercial953.github.io/gestion-comercial-biogreen/

## Contenido

Página autocontenida (un solo `index.html` con todo inline: CSS, JS, íconos y logo embebidos como data URI). No requiere servidor ni dependencias.

### Solapas

- **Resumen** — Configuración del ciclo, metas, banner guardado, Métricas para proyectar, Forecast editable, Avance a la fecha (con proyección semanal por Puntos y Facturación), barras vs Meta y vs Forecast, Comparativo de métricas.
- **Análisis Diario** — Gráfico de comportamiento diario (Puntos / Facturación) con proyectado desde histórico, hitos del ciclo, distribución por semana, comparativo interanual por ciclo.
- **Tipo de Ciclo** — Distribución histórica (semanal y diaria) por tipo de ciclo (Apertura / Medio N / Cierre) para 5 y 6 ciclos.

### Datos embebidos

Los datos reales (Ver Pedidos + hoja Inicio) están embebidos como snapshot al momento de la publicación. Para refrescar hay que regenerar el archivo con la nueva data.

## Actualizar

Reemplazar `index.html` con la versión nueva y hacer push. GitHub Pages sirve la home actualizada automáticamente.
