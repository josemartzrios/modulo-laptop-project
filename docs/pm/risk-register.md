# ⚠️ Risk Register - Módulo Laptop

> Registro de riesgos identificados y plan de mitigación.

---

## Matriz de Riesgos Activos

| ID | Riesgo | Probabilidad | Impacto | Severidad | Owner | Mitigación | Status |
|----|--------|--------------|---------|-----------|-------|------------|--------|
| R-001 | Demora en obtención usuario Admin | Media | Alto | 🔴 Crítico | Valentín | Escalamiento temprano, buscar alternativas de acceso | 🟢 Mitigado |
| R-002 | Problemas de compatibilidad imagen PC con periféricos Laptop | Alta | Alto | 🔴 Crítico | Equipo técnico | Validar post-instalación, tener imagen específica como Plan B | 🟡 Monitoreando |
| R-003 | Bugs críticos encontrados cerca del deadline | Alta | Alto | 🔴 Crítico | Manuel/Jorge | Buffer tiempo, solo impedimentos (no defectos), priorización P0 | ⬜ Pendiente |
| R-004 | Falta de documentación técnica existente | Baja | Medio | 🟡 Medio | José Francisco | Manual existente disponible, sesiones con Osvaldo | 🟢 Mitigado |
| R-005 | Dependencias de red/infraestructura | Media | Alto | 🔴 Crítico | TBD | Verificar conectividad temprana, Zscaler habilitado | ⬜ Pendiente |
| R-006 | Incompatibilidad drivers Morfo con laptop | Media | Alto | 🔴 Crítico | Proyectos Especiales | Manual validación dispositivos, posible imagen específica laptops | 🟡 Monitoreando |
| R-007 | Retraso en entrega componente escáner (equipo Roberto) | Media | Alto | 🔴 Crítico | N/A (externo) | Mismo deadline 6 Feb, coordinación constante | ⬜ Pendiente |
| R-008 | Plataforma no funcional inicialmente | Baja | Medio | 🟡 Medio | Gustavo López | No se usará al inicio, enfoque en flujos sin plataforma | ⬜ Aceptado |

---

## 🆕 Riesgos Identificados (Reunión 29/01)

| Riesgo | Descripción | Acción Inmediata |
|--------|-------------|------------------|
| Imagen basada en PC | La imagen Win11 fue creada para PC de módulo, no laptop | Validar periféricos post-instalación |
| Drivers Morfo adecuados | Morfo fue ajustado por Proyectos Especiales para PC | Posible imagen específica para laptops |
| Plataforma no usable | Mayor dificultad reportada es la plataforma | No usar inicialmente |

---

## Escala de Evaluación

### Probabilidad
| Nivel | Descripción |
|-------|-------------|
| Baja | < 25% de ocurrencia |
| Media | 25-50% de ocurrencia |
| Alta | > 50% de ocurrencia |

### Impacto
| Nivel | Descripción |
|-------|-------------|
| Bajo | Retraso < 1 día, workaround fácil |
| Medio | Retraso 1-2 días, requiere esfuerzo adicional |
| Alto | Retraso > 2 días, puede afectar deadline |

### Severidad (Probabilidad × Impacto)
| Color | Nivel | Acción |
|-------|-------|--------|
| 🟢 | Bajo/Mitigado | Monitorear |
| 🟡 | Medio | Plan de mitigación activo |
| 🔴 | Crítico | Escalamiento inmediato si ocurre |

---

## Historial de Riesgos Materializados

| Fecha | Riesgo | Impacto Real | Resolución | Lecciones Aprendidas |
|-------|--------|--------------|------------|---------------------|
| - | - | - | - | - |

---

## Contingency Plan

### Si se materializa R-002 (Incompatibilidad imagen):
1. Notificar inmediatamente a Proyectos Especiales
2. Solicitar imagen específica para laptops
3. Usar manual de validación dispositivos de Gustavo
4. Trabajar en paralelo en configuración manual de drivers

### Si se materializa R-003 (Bugs cerca del deadline):
1. Priorizar solo bugs críticos (P0) 
2. Documentar bugs P1/P2 para fase posterior 
3. Comunicar status transparente a stakeholders
4. Solo registrar impedimentos (no defectos - no hay cambio de código)

### Si se materializa R-006 (Drivers Morfo):
1. Contactar a Proyectos Especiales para adecuación
2. Usar manual de validación de Gustavo
3. Considerar workaround temporal

---

*Última actualización: 29/01/2026*
