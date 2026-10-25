# Prompt de auditoría: puerta M5 (Pruebas)

**Entrega a la IA:** requerimientos con criterios de aceptación, `casos-prueba.md`, resultados de ejecución, `trazabilidad.md`, reglas de negocio.

```
Actúa como ingeniero de QA senior. Audita la cobertura de pruebas del módulo [Mxx].

Revisa y reporta:
1. Criterios de aceptación sin caso de prueba.
2. Casos de prueba que no correspondan a ningún criterio.
3. Casos borde faltantes: valores límite, vacíos, duplicados, formatos inválidos, concurrencia, permisos por rol.
4. Reglas de negocio [IDs] sin caso que las verifique en positivo y en negativo.
5. Casos con resultado esperado ambiguo o no verificable.
6. Regresión: según las dependencias del módulo, qué casos de módulos anteriores deberían re-ejecutarse.
7. Resultados: fallas abiertas por severidad y si bloquean la puerta.

Genera, para cada hueco detectado, una propuesta de caso de prueba (ID provisional, pasos, resultado esperado).

[Pega aquí el bloque común de formato]
```
