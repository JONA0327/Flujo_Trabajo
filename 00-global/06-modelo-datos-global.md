---
id: GLOBAL-DATOS
módulo: GLOBAL
versión: v0.1
estado: borrador
responsable: [nombre]
revisor: [nombre distinto]
fecha: [AAAA-MM-DD]
---

# Modelo de datos global (entidades compartidas)

Regla: cada tabla compartida tiene un **módulo dueño**. Otros módulos pueden leerla o referenciarla, pero no modificar su estructura sin solicitud de cambio.

| Entidad / Tabla | Descripción | Módulo dueño | Módulos que la usan |
|---|---|---|---|
| users | Usuarios del sistema | M00 | todos |
| roles | Roles y permisos | M00 | todos |
| [catalogo_x] | [ ] | [Mxx] | [ ] |

## Relaciones clave
```mermaid
erDiagram
  USERS ||--o{ ROLES_USERS : tiene
  ROLES ||--o{ ROLES_USERS : asigna
```

## Reglas comunes
- Toda tabla lleva: `id`, `created_at`, `updated_at`, [`deleted_at` si hay borrado lógico], [`created_by`].
- [Convención de claves foráneas, nulos, tipos de dinero y fecha.]
