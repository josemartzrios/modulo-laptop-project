# Módulo de Traspaso y Afiliación - Laptops

## 📋 Información General

| Campo | Valor |
|-------|-------|
| **Proyecto** | Habilitación Módulo Traspaso y Afiliación en Laptops |
| **Deadline** | 6 de febrero 2026 |
| **Días restantes** | 8 días (al 29/01/2026) |
| **Status** | 🟡 En Progreso |

---

## 🎯 Objetivo

Habilitar y desplegar el Módulo de Traspaso y Afiliación en equipos tipo Laptop para el 6 de febrero, asegurando que el flujo sea funcional y estable para asesores provisionales del Afore.

### Definition of Done

- [ ] El flujo de registro y traspaso se ejecuta de principio a fin sin errores críticos en Laptops
- [ ] El flujo está documentado
- [ ] Smoke test completado (happy path)

---

## 👥 Equipo

| Rol | Nombre | Responsabilidades |
|-----|--------|-------------------|
| **Líder de Proyecto** | Valentín López Valenzuela | Gestión general, stakeholder management, coordinación Team Coach |
| **Arquitecto** | Carlos Oswaldo Pérez Hernández | Decisiones técnicas, validación arquitectura |
| **Coordinador** | Marcos Alberto Meza Medrano | Coordinación instalación imagen, ambiente de pruebas |
| **Developer** | Manuel Tinoco | Desarrollo, configuración, pruebas Traspaso |
| **Developer** | Jorge Ceballos | Desarrollo, configuración, pruebas Registro |
| **Analista** | José Francisco | Documentación, análisis, QA |
| **Tester (NTT DATA)** | Luis Alejandro Peraza Lizárraga | Smoke tests, happy path, bitácora impedimentos |
| **Soporte Imagen** | Gustavo López Cortez | Imagen Windows 11, manual validación dispositivos |
| **Infraestructura** | Daniel Soto | Instalación imagen en laptop |
| **Permisos** | Rigo | Gestión permisos carpetas usuario dominio |

---

## 🔧 Contexto Técnico

### Ambiente

- **Tipo de equipo**: Laptops (equipo oficial en campus, NO laptop personal)
- **Sistema Operativo**: Windows 11 (imagen de producción)
- **Estado del código**: Existente (en proceso de ambientación)
- **Esquema de trabajo**: Híbrido (requiere presencia en campus para pruebas)

### Componentes Técnicos

- **Escáner**: Drivers incluidos en imagen
- **Morfo (huella)**: Drivers incluidos, adecuados por Proyectos Especiales
- **Zscaler**: Debe estar habilitado
- **Plataforma**: No se usará inicialmente

### Dependencias Externas

- [x] Formato de permisos firmado (Rigo) ✅
- [ ] Imagen Windows 11 de producción (Gustavo López → Daniel Soto)
- [ ] Componente sustitución de escáner (Equipo Roberto - 6 Feb)  
- [ ] Acceso campus para Luis Alejandro (todo febrero)

---

### Frecuencia de Updates

- Daily check-ins 
- Demo final: 6 de febrero

---

## 📝 Changelog del Proyecto

| Fecha | Evento | Notas |
|-------|--------|-------|
| 28/01/2026 | Kickoff documentación PM | Setup inicial de tracking |
| 29/01/2026 | Reunión coordinación imagen Win11 | Acuerdos sobre instalación y pruebas |
| 29/01/2026 | Formato permisos enviado | Rigo completó envío |

---

## 📌 Referencias

- Tiendas con Windows 11 ya operativas con flujo de traspaso
- Manual de validación de dispositivos (Gustavo López)
- Manual de flujo para familiarización

---

*Última actualización: 29/01/2026*
