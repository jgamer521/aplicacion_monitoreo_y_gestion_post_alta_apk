# 📱 Aplicación Móvil de Monitoreo y Gestión Post-Alta – Clínica "El Carmen"

**Proyecto de Grado – Instituto Tecnológico Sacaba (Cochabamba, Bolivia)**  
**Estudiante:** Jhoel Jhon Limachi Flores  
**Tutor:** Lic. Nardy C. Miranda F.  
**Gestión:** 2025

---

## 🏥 Descripción General

La **Aplicación Móvil de Monitoreo y Gestión Post-Alta** es una herramienta desarrollada para la **Clínica “El Carmen”** con el objetivo de mejorar el **seguimiento médico de pacientes crónicos y post-quirúrgicos** después del alta hospitalaria.

Este sistema permite registrar síntomas, generar recordatorios inteligentes, habilitar comunicación directa entre médico y paciente, y emitir alertas tempranas para prevenir complicaciones.

Su implementación busca **reducir los reingresos hospitalarios en un 35%**, mejorar la adherencia a tratamientos y optimizar los recursos médicos mediante la automatización de tareas repetitivas.

---

## 🎯 Objetivo General

Desarrollar una aplicación móvil multiplataforma que facilite el monitoreo y la gestión post-alta en la Clínica “El Carmen”, mediante funcionalidades de registro clínico, comunicación médico-paciente y recordatorios automatizados, garantizando continuidad en la atención y mejora en la calidad de vida de los pacientes.

---

## 🧩 Objetivos Específicos

- Recopilar información sobre las necesidades post-alta de pacientes y médicos.
- Diseñar una aplicación móvil con interfaces intuitivas y accesibles.
- Implementar una base de datos segura y escalable mediante **Firebase Firestore**.
- Integrar notificaciones automáticas y recordatorios de medicación.
- Probar la aplicación con pacientes y personal médico mediante **A/B testing**.
- Elaborar un **manual de usuario** para facilitar su uso e instalación.

---

## ⚙️ Tecnologías y Herramientas Utilizadas

| Tipo | Herramienta / Tecnología |
|------|---------------------------|
| **Lenguaje** | Flutter (Dart) |
| **Base de Datos** | Firebase Firestore |
| **Autenticación** | Firebase Authentication |
| **Notificaciones** | Firebase Cloud Messaging (FCM) |
| **Gestión de Estado** | Patrón BLoC / flutter_bloc |
| **Diseño de Interfaces** | Figma |
| **Seguridad** | Cifrado AES-256 |
| **Control de Versiones** | Git y GitHub |
| **Pruebas** | flutter_test, JMeter, OWASP ZAP |
| **Administración de Proyecto** | Trello / Jira |

---

## 🧠 Metodología de Desarrollo

Se empleó la **Metodología Incremental**, permitiendo construir la aplicación en **módulos sucesivos (incrementos)**.  
Cada incremento fue validado por médicos y pacientes, garantizando la mejora continua del producto.

### Incrementos Principales:
1. **Gestión de Usuarios:** Registro, autenticación y roles (administrador, médico, paciente).  
2. **Monitoreo Clínico:** Registro diario de síntomas y signos vitales.  
3. **Recordatorios:** Alertas automáticas de medicación y citas médicas.  
4. **Comunicación Médica:** Chat seguro entre pacientes y médicos.  
5. **Reportes:** Generación de estadísticas sobre evolución y adherencia terapéutica.

---

## 🧑‍🤝‍🧑 Actores del Sistema

| Actor | Descripción | Funciones principales |
|--------|--------------|------------------------|
| **Paciente** | Usuario principal post-alta que registra síntomas y recibe recordatorios. | Registro de síntomas, consulta de evolución, comunicación con su médico. |
| **Médico** | Supervisa y analiza la evolución del paciente. | Revisión de registros, envío de recomendaciones, generación de reportes. |
| **Administrador** | Responsable técnico del sistema. | Gestión de usuarios, roles y configuraciones generales. |

---

## 📱 Funcionalidades Principales

- ✅ Registro y monitoreo de síntomas post-alta  
- 🔔 Recordatorios automáticos de medicación y citas  
- 💬 Chat seguro médico-paciente  
- 📊 Reportes de evolución clínica y adherencia  
- 🧾 Gestión de usuarios y roles  
- 🔐 Seguridad con autenticación y cifrado de datos  

---

## 🧪 Pruebas y Validación

Se realizaron pruebas de tipo:
- **Técnicas:** rendimiento, seguridad, compatibilidad multiplataforma.  
- **De usuario:** usabilidad con médicos y pacientes reales.  
- **Herramientas:** JMeter, OWASP ZAP, flutter_test, integration_test.

Resultados esperados:
- Reducción del **35% en reingresos hospitalarios**.  
- Mejora en la **adherencia a tratamientos médicos**.  
- Disminución de **costos operativos** y optimización de tiempos médicos.

---

## 🧭 Arquitectura del Sistema

La arquitectura del sistema está basada en una estructura **cliente-servidor**:
- **Frontend:** Flutter (Dart)
- **Backend:** Firebase (Firestore + Authentication + Cloud Messaging)
- **Gestión de Estado:** BLoC Pattern
- **Comunicación en tiempo real:** Streams y listeners de Firestore

---

## 📦 Instalación del Proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/jgamer521/aplicacion_monitoreo_y_gestion_post_alta_apk.git
