# EST-MOD-2026 · Demo pública

Demostración interactiva de la visión de un sistema de operación y administración de estacionamientos. **No es el sistema productivo.** Tickets, cobros, permisos, paystations, incidentes y reportes son simulados con datos ficticios del navegador.

- **Demostración:** https://highdiego666.github.io/EST-MOD-2026-DEMO/
- **Visión y hoja de ruta pública:** https://highdiego666.github.io/EST-MOD-2026-DEMO/vision.html

## Dirección actual · 22 de noviembre de 2026
El producto propuesto busca sustituir gradualmente el software heredado, empezando por **una sucursal**, con servicios operativos Linux y PostgreSQL en infraestructura propia, una plataforma administrativa web y un portal móvil de consulta/pago mediante proveedor externo.

El código de las integraciones productivas, autenticación, pagos electrónicos, adaptadores de barreras y paystations y la puesta en marcha real requieren desarrollo, pruebas y aceptación independientes. La expansión a más sucursales, pensiones, reconocimiento de placas y otras modalidades es posterior.

## Naturaleza de este repositorio
Esta publicación contiene la distribución estática de demostración, no el backend ni datos de la empresa. La página `vision.html` documenta el objetivo y la ruta previstos, sin asegurar que ya estén implementados.

Los archivos de `assets/` fueron generados por Vite y no deben editarse manualmente. La fuente principal se administra en un repositorio privado separado; después de cambios de frontend debe reconstruirse y sincronizarse esta distribución.
