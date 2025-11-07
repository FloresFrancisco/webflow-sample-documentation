# 🧰 Guía técnica — Mantenimiento y despliegue

## Stack
- **Frontend:** Webflow + integraciones personalizadas.
- **Backend:** Node.js + Express (API REST)
- **DB:** MongoDB Atlas
- **Infraestructura:** AWS (Lambda, S3, CloudFront, CodePipeline)

## Despliegue
1. Actualizar código en rama `main`.
2. Pipeline automático en CodePipeline:
   - Build → Test → Deploy.
3. Webflow se publica desde dashboard (manual trigger o API).

## Mantenimiento
- Backups diarios de la base de datos (MongoDB Atlas snapshot).
- Rotación de llaves API cada 90 días.
- Auditorías mensuales de rendimiento (Lighthouse).
