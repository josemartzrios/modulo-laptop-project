# ⚠️ Risk Register - Módulo Laptop

> Registro de riesgos identificados y plan de mitigación.

---

## Matriz de Riesgos Activos

| ID | Riesgo | Probabilidad | Impacto | Severidad | Owner | Mitigación | Status |
|----|--------|--------------|---------|-----------|-------|------------|--------|
| R-001 | Demora en obtención usuario Admin | Media | Alto | 🔴 Crítico | Valentín | Escalamiento temprano, buscar alternativas de acceso | 🟡 Monitoreando |
| R-002 | Problemas de compatibilidad con imagen prod | Media | Alto | 🔴 Crítico | Osvaldo | Pruebas tempranas en imagen real, tener rollback plan | ⬜ Pendiente |
| R-003 | Bugs críticos encontrados cerca del deadline | Alta | Alto | 🔴 Crítico | Manuel/Jorge | Buffer de tiempo para bug fixing, priorización estricta | ⬜ Pendiente |
| R-004 | Falta de documentación técnica existente | Baja | Medio | 🟡 Medio | José Francisco | Sesiones con Osvaldo para knowledge transfer | ⬜ Pendiente |
| R-005 | Dependencias de red/infraestructura | Media | Alto | 🔴 Crítico | TBD | Verificar conectividad temprana, tener contacto IT | ⬜ Pendiente |

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
| 🟢 | Bajo | Monitorear |
| 🟡 | Medio | Plan de mitigación activo |
| 🔴 | Crítico | Escalamiento inmediato si ocurre |

---

## Historial de Riesgos Materializados

| Fecha | Riesgo | Impacto Real | Resolución | Lecciones Aprendidas |
|-------|--------|--------------|------------|---------------------|
| - | - | - | - | - |

---

## Contingency Plan

### Si se materializa R-001 (Demora en Admin):
1. Escalar a Valentín inmediatamente
2. Buscar usuario alternativo con permisos  
3. Trabajar en paralelo en documentación mientras se resuelve

### Si se materializa R-003 (Bugs cerca del deadline):
1. Priorizar solo bugs críticos (P0) 
2. Documentar bugs P1/P2 para fase posterior 
3. Comunicar status transparente a stakeholders

---

*Última actualización: 28/01/2026*
