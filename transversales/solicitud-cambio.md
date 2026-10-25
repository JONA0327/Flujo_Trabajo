---
id: CHG-[###]
módulo: [Mxx, Mxx]
versión: v0.1
estado: borrador   # borrador | en análisis | pendiente de cliente | aprobada | rechazada | implementada
responsable: [quien analiza]
revisor: [nombre distinto]
fecha: [AAAA-MM-DD]
---

# CHG-[###]: [Título del cambio]

## 1. Solicitud
| Campo | Valor |
|---|---|
| Solicitante | [nombre, rol] |
| Fecha de solicitud | [ ] |
| Módulo(s) afectado(s) | [ ] |
| **Estado del módulo al solicitar** | futuro / en curso / entregado |
| Requerimientos afectados | [MOD]-RF-00x |

**Qué se quiere cambiar**
[Situación actual → situación deseada.]

**Por qué**
[Justificación de negocio.]

**Urgencia:** Alta / Media / Baja

## 2. Ruta según estado del módulo
| Estado | Ruta |
|---|---|
| Futuro | Se absorbe en M1 del módulo. Sin costo. Se documenta y se cierra. |
| En curso | Análisis de impacto, cotización y aprobación antes de programar. |
| Entregado | Análisis, cotización, nueva versión (v1.x) y regresión obligatoria. |

## 3. Análisis de impacto
| Área | ¿Afecta? | Detalle (documentos y elementos que se tocan) |
|---|---|---|
| Alcance / requerimientos | Sí/No | [IDs] |
| Casos de uso y reglas de negocio | Sí/No | [IDs] |
| Mockups / UI | Sí/No | [ ] |
| Base de datos | Sí/No | [tablas; ¿de otro módulo?] |
| Contrato de API | Sí/No | [endpoints] |
| Código ya desarrollado | Sí/No | [ ] |
| Pruebas y regresión | Sí/No | [casos] |
| Otros módulos | Sí/No | [ ] |
| Cronograma | Sí/No | [+N días] |

**Riesgos del cambio:** [ ]
**Alternativa más barata (si existe):** [ ]

## 4. Estimación
| Concepto | Horas | Costo |
|---|---|---|
| Documentación y diseño | | |
| Desarrollo | | |
| Pruebas y regresión | | |
| **Total** | | |

Impacto en fecha de entrega: [ ]

## 5. Decisión del cliente
☐ Aprobada  ☐ Rechazada  ☐ Pospuesta
Comentarios: [ ]
Nombre: [ ]  Firma: [ ]  Fecha: [ ]

## 6. Implementación
- Nueva versión de línea base: [v1.x]
- Documentos actualizados: [lista]
- Sprint / fecha de implementación: [ ]
- Etiqueta Git: [Mxx-baseline-v1.x]
- Pruebas de regresión ejecutadas: ☐
