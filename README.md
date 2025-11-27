# 🛡️ Plan de Respuesta a Incidentes de Ransomware basado en NIST

**Autor:** Arturo Martín-Vegue González  
**Fecha:** Noviembre 2025  
**Formación:** 4Geeks Academy - Ciberseguridad

---

Este repositorio aloja el desarrollo completo de un Plan de Respuesta a Incidentes (IRP) diseñado para gestionar y mitigar un ataque de *ransomware* crítico en un entorno corporativo simulado.

Proyecto realizado como parte del **Bootcamp de Ciberseguridad de 4Geeks Academy**.

## 📝 Descripción del Proyecto

El objetivo principal es establecer un procedimiento estructurado bajo el **Marco de Ciberseguridad del NIST** para que la organización ficticia (TechCo) pueda detectar, contener y recuperarse de un ataque de *ransomware*, transformando el incidente en una oportunidad de mejora.

### Puntos Clave Abordados

* **Análisis del Incidente:** Estudio del vector de ataque (*Phishing*), la propagación lateral por falta de segmentación y el cifrado de backups.
* **Estrategia de Protección:** Implementación de VLANs, DMZ y políticas de *Zero Trust* (Menor Privilegio).
* **Detección Avanzada:** Uso de FIM (Monitoreo de Integridad) y correlación de eventos (SIEM) para alerta temprana.
* **Respuesta y Recuperación:** Protocolos de aislamiento y restauración estratégica a un estado *Pre-Compromiso* (asumiendo pérdida de datos por seguridad).
* **Mejora Continua:** Creación de Planes de Acción Correctiva (PAC) y auditorías post-incidente.

## 🛠️ Conceptos y Tecnologías

* **NIST Cybersecurity Framework** (Identify, Protect, Detect, Respond, Recover)
* **SIEM** (Security Information and Event Management)
* **EDR** (Endpoint Detection and Response)
* **FIM** (File Integrity Monitoring)
* **VLAN / DMZ** (Segmentación de Red)
* **Air-Gapped Backups** (Copias inmutables/desconectadas)

## 📂 Estructura del Repositorio

* `Plan_de_Respuesta_a_Incidentes_de_Ransomware_basado_en_NIST.pdf`: Contiene el informe completo con el análisis del caso TechCo y la propuesta de resolución detallada paso a paso.
