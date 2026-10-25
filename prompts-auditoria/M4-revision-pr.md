# Prompt de auditoría: puerta M4 (Desarrollo, por PR)

**Entrega a la IA:** el diff del PR, el requerimiento e historia referenciados con sus criterios de aceptación, el fragmento de `api.yaml` y reglas de negocio aplicables, y el estándar de código (`05-arquitectura-base.md`).

```
Actúa como revisor de código senior. Revisa este PR contra su requerimiento [ID] e historia [ID].

Revisa y reporta:
1. Cada criterio de aceptación: ¿está implementado? ¿dónde (archivo y línea)? ¿cuál falta?
2. Código que NO corresponde al requerimiento (funcionalidad extra, código muerto, imports o métodos sin uso, comentarios de código desactivado).
3. Desviaciones del contrato de API (rutas, campos, códigos HTTP, formato de error).
4. Reglas de negocio [IDs] aplicadas incorrectamente o ausentes.
5. Validaciones, manejo de errores y permisos faltantes.
6. Riesgos de seguridad (inyección, autorización, datos sensibles) y de rendimiento (consultas N+1, falta de índices).
7. Violaciones de las convenciones del proyecto.
8. Pruebas automatizadas faltantes para cada criterio de aceptación.

[Pega aquí el bloque común de formato]
```
