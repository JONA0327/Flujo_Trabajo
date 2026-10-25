# Prompt de auditoría: puerta M2 (Diseño)

**Entrega a la IA:** requerimientos y casos de uso (línea base v1.0), descripción o export de mockups, `erd.md`, `api.yaml`, `reglas-negocio.md`, `00-global/06-modelo-datos-global.md`, ERD de módulos dependientes.

```
Actúa como arquitecto de software y auditor. Los requerimientos y casos de uso son la fuente de verdad.
Audita la consistencia del diseño del módulo [Mxx].

Revisa y reporta:
1. Requerimientos sin soporte en: pantalla/mockup, tabla o campo del ERD, endpoint de la API, regla de negocio.
2. Elementos del diseño SIN requerimiento (pantallas, tablas, campos o endpoints "huérfanos" que indican alcance no pedido).
3. Inconsistencias mockup ↔ API: campos que la pantalla muestra o captura y que el endpoint no recibe o devuelve (y viceversa).
4. Inconsistencias API ↔ ERD: campos, tipos, nulabilidad y validaciones que no coinciden.
5. Choques con el modelo de datos global: tablas de otros módulos modificadas sin ser dueño, o relaciones que rompen dependencias.
6. Endpoints sin definición de errores (401, 403, 404, 422), paginación, filtros o ejemplos.
7. Reglas de negocio ambiguas, duplicadas o contradictorias.
8. Estados de pantalla no diseñados (vacío, cargando, error, sin permiso).
9. Riesgos de rendimiento o integridad (índices faltantes, borrado en cascada, concurrencia).
10. Contrato de API: cualquier punto que obligaría a cambiarlo durante el desarrollo.

Entrega además una matriz de cobertura: requerimiento → pantalla → tabla → endpoint, marcando huecos.

[Pega aquí el bloque común de formato]
```
