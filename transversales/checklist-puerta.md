---
id: PUERTA-[Mxx]-[M#]
módulo: [Mxx]
versión: v1
estado: borrador
responsable: [quien produjo]
revisor: [quien aprueba, distinto]
fecha: [AAAA-MM-DD]
---

# Checklist de puerta: [Mxx] / [Nombre de la puerta]

Regla: la puerta se cierra solo con todos los criterios cumplidos, el reporte de auditoría IA revisado y la firma humana. **Deja solo la sección de la puerta que corresponde.**

**Reporte de auditoría asociado:** `auditorias/[archivo].md`
**Hallazgos críticos abiertos:** [0]

---
## GLOBAL: Descubrimiento
- [ ] Carta constitutiva con fuera de alcance explícito
- [ ] Mapa de procesos AS-IS y TO-BE
- [ ] Mapa de módulos con dependencias y orden
- [ ] Roadmap e hitos de pago acordados
- [ ] Arquitectura base y modelo de datos global con módulo dueño por tabla
- [ ] Cliente firmó mapa de módulos y roadmap

## M1: Requerimientos
- [ ] Todos los requerimientos tienen ID y criterio de aceptación verificable
- [ ] Casos de uso cubren todos los requerimientos
- [ ] Sin contradicciones (auditoría IA revisada)
- [ ] Preguntas abiertas que afecten requerimientos Must: 0
- [ ] Fuera de alcance del módulo declarado
- [ ] Cliente firmó línea base v1.0

## M2: Diseño
- [ ] Mockups cubren todos los casos de uso, con estados vacío/error/éxito
- [ ] Cliente aprobó el prototipo
- [ ] ERD consistente con mockups y casos de uso
- [ ] Sin conflictos con tablas de otros módulos
- [ ] Contrato de API completo y **congelado**
- [ ] Reglas de negocio numeradas
- [ ] Trazabilidad sin celdas vacías hasta este punto
- [ ] Equipo aprobó ERD y API (revisión cruzada)

## M3: Planeación
- [ ] Cada historia referencia un requerimiento y tiene criterios
- [ ] Cada requerimiento tiene al menos una historia
- [ ] Estimación y orden acordados
- [ ] Definición de "Hecho" confirmada

## M4: Desarrollo (por PR)
- [ ] PR referencia ID de requerimiento o historia
- [ ] Cumple el contrato de API
- [ ] Sin código muerto ni fuera de alcance
- [ ] Linter y análisis estático limpios
- [ ] Pruebas automatizadas incluidas
- [ ] Revisado por alguien distinto al autor

## M5: Pruebas
- [ ] Todo criterio de aceptación tiene caso de prueba
- [ ] Todos los casos ejecutados y pasan
- [ ] Regresión de módulos anteriores pasa
- [ ] Sin bugs críticos ni altos abiertos
- [ ] Casos borde y de permisos cubiertos

## M6: Aceptación y entrega
- [ ] Demo realizada al cliente
- [ ] Desviaciones vs. línea base documentadas
- [ ] Documentación refleja lo construido
- [ ] Acta firmada por el cliente
- [ ] Módulo marcado como **congelado** y etiqueta Git creada
- [ ] Hito de pago emitido

---
## Evidencia
| Criterio | Evidencia (enlace / archivo) |
|---|---|

## Decisión
☐ Puerta aprobada  ☐ Regresa a la etapa anterior
Motivo / condiciones: [ ]
Aprobador: [ ]  Fecha: [ ]
