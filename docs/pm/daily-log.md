# 📅 Daily Log - Módulo Laptop

> Registro diario de actividades, updates y notas.

---

## 30/01/2026 (Jueves) - Día 3

### 📊 Status: 🟢 On Track

### ✅ Completado Hoy
- ✅ Recepción correo de Daniel Castro con componentes de Desarrollos Especiales
- ✅ Toma de huellas funcional en flujo de afiliación
- ✅ Eliminada dependencia del archivo `Locks.max` (ya no se requiere)
- ✅ Usuario con permisos para laptop configurado

### 🚀 En Progreso
- Instalación de imagen Windows 11 en laptop
- Carta excepción para permisos admin en `c:\sys` y `c:\temp` (Alberto Cebreros)

### 📋 Componentes Técnicos Confirmados (Desarrollos Especiales)

**Ejecutable:**
- `HE442SVR.EXE` → `c:\sysprogs`

**DLLs (copiar a 3 rutas):**
| DLL | Ruta 1 | Ruta 2 | Ruta 3 |
|-----|--------|--------|--------|
| Lmaxw.dll | `\windows\syswow64` | `c:\windows\system32` | `c:\sys\progs\depdll` |
| Lmaxw2008.dll | `\windows\syswow64` | `c:\windows\system32` | `c:\sys\progs\depdll` |
| Lmaxw2010.dll | `\windows\syswow64` | `c:\windows\system32` | `c:\sys\progs\depdll` |
| Lmaxw2012.dll | `\windows\syswow64` | `c:\windows\system32` | `c:\sys\progs\depdll` |
| Lmaxw2013.dll | `\windows\syswow64` | `c:\windows\system32` | `c:\sys\progs\depdll` |
| Lmaxw2017.dll | `\windows\syswow64` | `c:\windows\system32` | `c:\sys\progs\depdll` |

### 🎯 Próximos Pasos
- [ ] Completar instalación de imagen Win11
- [ ] Validar periféricos post-instalación
- [ ] Obtener carta excepción para permisos admin

### ⚠️ Blockers
- Carta excepción pendiente para permisos en `c:\sys` y `c:\temp`

### 📝 Notas
- Alberto Sillas de Desarrollos Especiales ayudó con revisiones de código
- Las versiones de DLLs son las últimas liberadas por Desarrollos Especiales
- **Hallazgo importante:** La dependencia de `Locks.max` en `C:\` era por versiones antiguas, ya NO se requiere

### 📌 Pendientes HOY

| # | Pendiente | Owner | Status |
|---|-----------|-------|--------|
| 1 | Completar instalación imagen Win11 | Daniel Soto | 🟡 En progreso |
| 2 | Carta excepción permisos admin c:\sys y c:\temp | Alberto Cebreros | ✅ Completado |
| 3 | Validar periféricos post-instalación | Equipo técnico | ⬜ Pendiente |

---


## 29/01/2026 (Miércoles) - Día 2

### 📊 Status: 🟢 On Track

### ✅ Completado Hoy
- Reunión de coordinación imagen Windows 11
- Rigo envió formato de permisos firmado
- Gustavo confirmó disponibilidad de imagen Win11
- Documentación de minuta de reunión

### 🚀 En Progreso
- Gustavo enviando imagen Win11 a Daniel Soto
- Luis Alejandro solicitando acceso campus (febrero)
- Valentín agendando reunión con Team Coach (Julio César)

### 🎯 Próximos Pasos
- [ ] Daniel Soto recibe imagen Win11 (30 Ene)
- [ ] Instalar imagen en laptop oficial del campus
- [ ] Validar periféricos post-instalación
- [ ] Luis Alejandro: familiarizarse con manual de flujo

### ⚠️ Blockers
- Ninguno crítico para instalación de imagen (se puede usar cualquier usuario)

### 📝 Notas
- ⚠️ Riesgo: Imagen basada en PC puede tener problemas con periféricos de laptop
- Laptop oficial será la del campus, NO usar laptop personal
- Solo se registrarán impedimentos (no defectos) ya que no se mueve código
- **Daniel Castro** enviará correo con componentes y modificaciones de Desarrollo Especiales

### 📌 Pendientes HOY

| # | Pendiente | Owner | Status |
|---|-----------|-------|--------|
| 1 | Instalar imagen Win11 en laptop (ambientar máquina) | Daniel Soto | ⬜ |
| 2 | Alta de usuarios programadores con permisos sys/temp (carta firmada) | Alberto Cebreros | ⬜ |
| 3 | Solicitar acceso campus febrero | Luis Alejandro (NTT) | ⬜ |
| 4 | Agendar reunión Agile Coach (Julio César) | José Francisco | ✅ Agendada 30 Ene 10:30 |
| 5 | Familiarizarse con flujo usando manual | Luis Alejandro (NTT) | ⬜ |
| 6 | Correo componentes Desarrollo Especiales | Daniel Castro | ⬜ |
| 7 | Sesión Agile Coach con tareas definidas | Valentín + Equipo | 📅 Mañana 10:30 |

---

## 28/01/2026 (Martes) - Día 1

### 📊 Status: 🟡 En Progreso

### ✅ Completado Hoy
- Setup inicial de documentación PM
- Creación de estructura de tracking
- T-01: Solicitud archivos ambiente espejo ✅
- T-02: Cronograma de seguimiento ✅

### 🚀 En Progreso
- Gestión de usuario Admin para máquina de pruebas
- Equipo realizando ambientación
- Sesión con Gustavo para obtener imagen de Windows 11

### 🎯 Próximos Pasos
- [x] Completar obtención de accesos

### ⚠️ Blockers
- Ninguno crítico

### 📝 Notas
- Deadline: 6 de febrero (9 días restantes)
- Equipo completo asignado

---

## Countdown

| Fecha | Días Restantes | Hito Esperado | Status |
|-------|----------------|---------------|--------|
| 28/01 | 9 | Inicio documentación | ✅ |
| 29/01 | 8 | Coordinación imagen Win11 | ✅ |
| 30/01 | 7 | Recepción e instalación imagen | 🟡 En progreso |
| 31/01 | 6 | Validación periféricos | ⬜ |
| 03/02 | 3 | Inicio pruebas (smoke test) | ⬜ |
| 04/02 | 2 | Bug fixing / impedimentos | ⬜ |
| 05/02 | 1 | Validación final | ⬜ |
| 06/02 | 0 | 🚀 LAUNCH | ⬜ |

---

*Documento actualizado diariamente*
