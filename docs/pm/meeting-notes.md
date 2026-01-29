# 📝 Meeting Notes - Módulo Laptop

> Registro de minutas de reuniones del proyecto.

---

## 29/01/2026 - Coordinación Imagen Windows 11 y Ambiente de Pruebas

**Fecha:** 29 de enero 2026  
**Asistentes:** 
- Marcos Alberto Meza Medrano
- Gustavo López Cortez
- Carlos Oswaldo Pérez Hernández
- Luis Alejandro Peraza Lizárraga (NTT DATA)
- Valentín López Valenzuela
- Daniel Soto
- Rigo

**Objetivo:** Coordinar instalación de imagen Windows 11 en laptop para módulo de afiliación y traspasos

---

### 📋 Temas Discutidos

#### 1. Imagen de Windows 11
- Gustavo López confirmó disponibilidad de imagen Windows 11
- La imagen será enviada a Daniel Soto (entre 29-30 enero)
- URL de imagen disponible en manual que Gustavo compartirá
- ⚠️ **Riesgo identificado:** La imagen está basada en PC de módulo, podría causar inconvenientes con periféricos de laptop (cámara, Morfo)

#### 2. Componentes y Drivers
- Imagen instalada de cero con drivers para escáner y Morfo
- Incluye actualizaciones de plataforma
- Componentes Morfo fueron adecuados por área de proyectos especiales
- **Decisión:** Podría requerirse imagen específica para laptops
- Manual de validación de dispositivos ayudará con validación del Morfo

#### 3. Permisos y Accesos
- Rigo ya envió formato con firmas para solicitar permisos de lectura/escritura
- Permisos requeridos para ciertas carpetas del usuario de dominio
- Objetivo: evitar problemas de permisos durante pruebas

#### 4. Ambiente de Prueba
- **Laptop oficial:** Se configurará en el campus (NO usar laptop personal de Luis Alejandro)
- Luis Alejandro debe familiarizarse con flujo usando manual existente
- Objetivo: asegurar que imagen funcione sin manipulaciones

#### 5. Alcance de Pruebas
- Luis Alejandro realizará **smoke tests** (pruebas de humo)
- Enfoque en "happy path" del flujo de afiliación
- Registrar todos los sucesos e impedimentos en bitácora
- No se mueve código a nueva infraestructura → solo impedimentos, no defectos

#### 6. Esquema de Trabajo y Acceso al Campus
- Equipo trabaja en esquema híbrido
- Luis Alejandro requerirá presencia en campus para pruebas
- Solicitará acceso al campus para todo febrero

#### 7. Historias de Usuario y Jira
- Equipo trabajando en listado de actividades para historias de usuario
- Pendiente reunión con Julio César (Team Coach) para definir plantilla
- Valentín buscará espacio en agenda de Julio César

---

### ✅ Acuerdos Alcanzados

| # | Acuerdo | Responsable | Fecha |
|---|---------|-------------|-------|
| 1 | Enviar imagen Windows 11 a Daniel Soto | Gustavo López | 29-30 Ene |
| 2 | Compartir manual con URL de imagen | Gustavo López → Marcos Alberto | 29 Ene |
| 3 | Instalar imagen en laptop oficial | Daniel Soto + Marcos Alberto | Por definir |
| 4 | Enviar formato de permisos firmado | Rigo | ✅ Completado |
| 5 | Solicitar acceso al campus (Feb completo) | Luis Alejandro Peraza | 29 Ene |
| 6 | Agendar reunión con Team Coach (Julio César) | Valentín López | 29 Ene |
| 7 | Laptop de pruebas será la del campus | Equipo | Confirmado |
| 8 | Usar manual existente para familiarización | Luis Alejandro | Inmediato |
| 9 | Enviar correo con lista de componentes y modificaciones de Desarrollo Especiales | Daniel Castro | 29 Ene |
| 10 | Nueva sesión con Agile Coach con tareas definidas | Valentín + Equipo | 29 Ene |

---

### 📌 Pendientes / Action Items

| ID | Pendiente | Owner | Fecha Límite | Status |
|----|-----------|-------|--------------|--------|
| P-01 | Recibir imagen Windows 11 | Daniel Soto | 30 Ene | ⬜ Pendiente |
| P-02 | Instalar imagen en laptop campus | Daniel Soto | Por definir | ⬜ Pendiente |
| P-03 | Validar compatibilidad de periféricos (Morfo, cámara) | Equipo técnico | Post-instalación | ⬜ Pendiente |
| P-04 | Solicitar acceso campus febrero | Luis Alejandro | 29 Ene | ⬜ Pendiente |
| P-05 | Reunión Team Coach - definir plantilla Jira | Valentín + Julio César | 29 Ene | ⬜ Pendiente |
| P-06 | Familiarizarse con flujo (manual) | Luis Alejandro | Pre-pruebas | ⬜ Pendiente |
| P-07 | Crear bitácora de impedimentos | Luis Alejandro | Inicio pruebas | ⬜ Pendiente |
| P-08 | Enviar correo componentes y modificaciones Desarrollo Especiales | Daniel Castro | 29 Ene | ⬜ Pendiente |
| P-09 | Sesión Agile Coach con tareas definidas | Valentín + Equipo | 29 Ene | ⬜ Pendiente |

---

### 📝 Notas Importantes

- **Deadline proyecto:** 6 de febrero 2026
- **Dependencia crítica:** Componente de sustitución de escáner (equipo de Roberto) - mismo deadline
- **Tiendas con Win11:** Ya hay tiendas completas funcionando con traspaso en módulo
- **Mayor dificultad reportada:** La plataforma (no se usará inicialmente)

---

*Minuta elaborada: 29/01/2026*
