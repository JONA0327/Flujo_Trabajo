# Prompt de apoyo: análisis de impacto de una solicitud de cambio

**Entrega a la IA:** la solicitud de cambio, línea base vigente del módulo, `trazabilidad.md`, `erd.md`, `api.yaml`, ERD de módulos que dependen de este.

```
Actúa como arquitecto y analista de impacto. Analiza la solicitud de cambio [CHG-###] sobre el módulo [Mxx]
(estado: [futuro/en curso/entregado]).

Con ayuda de la matriz de trazabilidad, reporta:
1. Requerimientos, casos de uso, reglas de negocio, pantallas, tablas, endpoints, historias y casos de prueba afectados (por ID).
2. Si el cambio contradice algún requerimiento firmado.
3. Impacto en otros módulos por dependencias de datos o API.
4. Casos de regresión que deberían re-ejecutarse.
5. Código ya desarrollado que se vería afectado (si se proporciona).
6. Riesgos y una alternativa de menor impacto, si existe.
7. Un rango de esfuerzo por área (documentación, desarrollo, pruebas) con los supuestos usados.

No decidas si el cambio se aprueba. Solo entrega el análisis para que lo revisemos nosotros y el cliente.
```
