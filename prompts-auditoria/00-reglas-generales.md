# Reglas generales para auditar con IA

1. **Entrega los documentos completos** de la etapa y de la anterior (la fuente de verdad). No resúmenes.
2. **Una puerta por conversación.** Evita mezclar módulos.
3. **Exige evidencia:** cada hallazgo debe citar IDs o fragmentos exactos. Descarta hallazgos sin cita.
4. **Pide que distinga** entre "contradicción comprobable" y "sospecha".
5. **Verifica tú los hallazgos críticos.** La IA puede alucinar o pasar cosas por alto.
6. **Guarda el resultado** en `auditorias/` con la plantilla `reporte-auditoria-ia.md`.
7. **La decisión de avanzar y la firma son humanas.**

## Bloque común (pégalo al final de cada prompt)

```
Formato de respuesta:
- Tabla de hallazgos con columnas: #, Severidad (Crítico/Alto/Medio/Bajo), Tipo
  (Contradicción/Faltante/Ambigüedad/Riesgo), Descripción, IDs o citas exactas, Corrección sugerida.
- Solo reporta lo que puedas sustentar con una cita literal de los documentos.
  Si es una sospecha, márcala como "Sospecha".
- No inventes requerimientos, campos ni endpoints que no estén en los documentos.
- Termina con: (1) lista de preguntas para el cliente, (2) conteo de hallazgos por severidad,
  (3) tu recomendación de si la puerta puede cerrarse, aclarando que la decisión final es humana.
```
