# Gestión Comercial Biogreen

Dashboard interno de seguimiento diario de ventas y metas.

**URL:** https://comercial953.github.io/gestion-comercial-biogreen/

## Acceso

🔒 **Contenido protegido con contraseña.** El HTML se sirve cifrado con AES-256-GCM
(clave derivada por PBKDF2-SHA256, 250.000 iteraciones). Sin la contraseña correcta
no se puede leer el contenido, ni siquiera descargando el archivo.

La contraseña no está almacenada en ningún lugar (ni en el repo, ni en el servidor).
Si se pierde, hay que regenerar el archivo desde el fuente original.

## Contenido (una vez descifrado)

Página autocontenida — un solo `index.html` con todo inline (CSS, JS, íconos y logo
embebidos como data URI). No requiere servidor ni dependencias.

### Solapas

- **Resumen** — Configuración del ciclo, metas, banner guardado, Métricas para
  proyectar, Forecast editable, Avance a la fecha (con proyección semanal por Puntos
  y Facturación + fila total), barras vs Meta y vs Forecast, Comparativo de métricas.
- **Análisis Diario** — Gráfico de comportamiento diario (toggle Puntos / Facturación)
  con proyectado desde histórico, hitos del ciclo, distribución por semana,
  comparativo interanual por ciclo.
- **Tipo de Ciclo** — Distribución histórica (semanal y diaria) por tipo de ciclo
  (Apertura / Medio N / Cierre) para catálogos de 5 y 6 ciclos.

### Datos embebidos

Los datos reales (Ver Pedidos + hoja Inicio + Ventas Ciclos) están embebidos como
snapshot al momento de la publicación. Para refrescar hay que regenerar el archivo
con la nueva data.
