# Portafolio de Ciberseguridad & SOC — José Aurelio Hernández Mendoza

¡Bienvenido! Soy estudiante del último semestre de **Ingeniería en Sistemas Computacionales** en el Instituto Tecnológico de San Luis Potosí, con especialidad en **Ciberseguridad** (INTE-CBS-2021-01) y enfocado en **Operaciones de Seguridad (SOC) e Ingeniería de Detección**.

---

## 🛠️ Habilidades Técnicas & Herramientas

* **SIEM & Threat Intelligence:** Wazuh SIEM (Manager, Indexer, Dashboard), File Integrity Monitoring (FIM), Reglas XML de correlación, Integración de VirusTotal API v3.
* **NIDS & Ingeniería de Detección:** Suricata 8.0 (Firma de reglas personalizadas `local.rules`, ingesta JSON `eve.json`).
* **Análisis de Tráfico & Protocolos:** Wireshark, tcpdump, Microsoft Pktmon (ETW), Análisis de Three-Way Handshake TCP, DNS, HTTPS/TLS 1.2.
* **Telemetría & Monitoreo de Infraestructura:** Zabbix 7.0 Server, Zabbix Agent 2, Triggers de rendimiento y depuración de red/firewall (TCP 10050).
* **Sistemas Operativos & Entornos:** Ubuntu Server 24.04 LTS, Windows 11 Pro, Kali Linux, VMware Workstation.

---

## 🚀 Proyectos Destacados de Ciberseguridad

### 1. Laboratorio SIEM, FIM & Threat Intelligence (Wazuh + VirusTotal API)
* **Despliegue & Monitoreo:** Instalación centralizada de Wazuh Server sobre Ubuntu Server y despliegue de agente en endpoint físico Windows 11.
* **Auditoría FIM & Reglas Custom:** Configuración de *File Integrity Monitoring* en tiempo real (`syscheck`) y creación de reglas XML personalizadas para correlacionar ataques de fuerza bruta.
* **Integración de Threat Intelligence:** Conexión con la API de VirusTotal para auditar firmas de malware en tiempo real (EICAR), elevando automáticamente alertas críticas a Nivel 12.

### 2. Detección de Intrusiones e Ingesta NIDS (Suricata + Wazuh)
* **Detection Engineering:** Configuración de Suricata NIDS en Ubuntu Server sobre la interfaz `ens33`.
* **Reglas Personalizadas:** Creación y prueba de firmas locales (`sid: 1000001`) para detectar accesos no autorizados a rutas sensibles (`/admin_secret`).
* **Centralización SIEM:** Ingesta y correlación de registros JSON (`eve.json`) hacia Wazuh Dashboard.

### 3. Telemetría de Infraestructura Híbrida (Zabbix 7.0 + Zabbix Agent 2)
* **Despliegue Híbrido:** Configuración de Zabbix Server con backend MariaDB y Zabbix Agent 2 en Windows 11.
* **Solución de Problemas:** Resolución de rechazos de conexión en puerto TCP 10050 y reglas de subred en `Zabbix Agent 2`.
* **Telemetría & Triggers:** Creación de disparadores personalizados para uso de CPU (>50% y >15%), monitoreo de memoria RAM y auditoría de reinicios de servicio.

### 4. Análisis Forense de Tráfico & Inspección de Protocolos
* **Análisis de Paquetes (PDF):** Captura y auditoría con Wireshark, tcpdump y Microsoft Pktmon (ETW).
* 🎥 **Demostración Práctica en Video de extracción de objetos HTTP:** [Ver Vídeo en Google Drive: Extracción de Objetos HTTP con Wireshark](https://drive.google.com/file/d/1wJ6kFAt55ah4vLdda-uHfyU3VTaHNlVg/view?usp=sharing)

---

## 📄 Reportes Técnicos de Laboratorio (PDF)

* 🛡️ **Wazuh SIEM & Threat Intelligence:** [Ver Reporte PDF](./Aurelio_Hernandez_Reporte_Wazuh_SIEM_VirusTotal.pdf)
* 📊 **Monitoreo con Zabbix 7.0:** [Ver Reporte PDF](./Aurelio_Hernandez_Laboratorio_Monitoreo_Zabbix7.pdf)
* 🦈 **Análisis Forense con Wireshark/tcpdump:** [Ver Reporte PDF](./Aurelio_Hernandez_Analisis_Trafico_Wireshark_tcpdump.pdf)
* 🚨 **Ingeniería de Detección con Suricata NIDS:** [Ver Reporte PDF](./Aurelio_Hernandez_Implementacion_Suricata_NIDS_Wazuh.pdf)

---

## 📬 Contacto 
* **Correo:** Jahurelio0811@gmail.com
* **Ubicación:** San Luis Potosí, México

