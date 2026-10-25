---
id: GLOBAL-ARQ
módulo: GLOBAL
versión: v0.1
estado: borrador
responsable: [nombre]
revisor: [nombre distinto]
fecha: [AAAA-MM-DD]
---

# Arquitectura base

## 1. Stack
| Capa | Tecnología | Versión |
|---|---|---|
| Backend | [ ] | [ ] |
| Frontend | [ ] | [ ] |
| Base de datos | [ ] | [ ] |
| Infraestructura / hosting | [ ] | [ ] |

## 2. Ambientes
| Ambiente | Propósito | URL | Quién despliega |
|---|---|---|---|
| Local | Desarrollo | n/a | Cada dev |
| Staging | Demos y UAT con el cliente | [ ] | [ ] |
| Producción | Uso real | [ ] | [ ] |

## 3. Convenciones de código
- Estilo / linter: [ ]
- Nombres de tablas y campos: [ ]
- Estructura de carpetas: [ ]

## 4. Estándar de API
- Estilo: [REST / GraphQL]
- Contrato en: `modulos/Mxx/03-diseno/api.yaml` (OpenAPI), **congelado antes de programar**
- Respuesta exitosa: `{ "data": ..., "meta": ... }`
- Respuesta de error: `{ "error": { "code": "...", "message": "...", "details": [] } }`
- Códigos HTTP usados: [ ]
- Paginación / filtros / orden: [ ]
- Versionado: [ ]

## 5. Autenticación y autorización
[Mecanismo, expiración de sesión, modelo de roles y permisos.]

## 6. Manejo de errores y logs
[ ]

## 7. Estrategia de ramas y PRs
- `main`: producción. `develop`: integración. `feature/[ID-historia]-[descripcion]`.
- Todo PR referencia un ID de requerimiento o historia. **Sin ID, no se mergea.**
- Tamaño máximo sugerido de PR: [ ] líneas. Revisor distinto al autor.

## 8. Definición de "Hecho" (global)
- [ ] Cumple los criterios de aceptación de su requerimiento
- [ ] Pasa linter y análisis estático
- [ ] Tiene pruebas automatizadas
- [ ] Respeta el contrato de API
- [ ] Sin código muerto ni fuera de alcance
- [ ] PR revisado y aprobado
- [ ] Documentación del módulo actualizada

## 9. Seguridad, respaldos y datos
[ ]
