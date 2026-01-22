# 📝 Notas de Lanzamiento - KDevTools

## [Versión 1.1.0] - proyectado
### ✨ Novedades
- **Actualizaciones Automáticas**: Integración con Sparkle para mantener la app siempre al día.
- **Nuevo Tema Visual**: Rediseño premium completo con paleta de colores personalizada (Teal, Navy Blue y Blanco). Se han actualizado todos los componentes y herramientas para una experiencia visual cohesiva.
- **Mejoras en la UI**: Optimizaciones en la barra lateral y navegación.

### 🛠️ Correcciones
- Corregido error de importación de Combine en el modelo de actualización.
- Ajustes menores en el formateador de JSON.

---

### Instrucciones para el despliegue:
1. Incrementa el `MARKETING_VERSION` en Xcode.
2. Exporta la app y comprímela en un `.zip`.
3. Mueve el `.zip` a `/Users/stevenaizaga/Documents/KDevTools/updates`.
4. Ejecuta `./publish_update.sh`.
