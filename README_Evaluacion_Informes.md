# 📊 Evaluación de Informes de Ciberseguridad – Cisco CyberOps

Este repositorio documenta el laboratorio del módulo **24.1 del curso Cisco CyberOps**, orientado al análisis de fuentes de inteligencia de amenazas cibernéticas. Se revisan informes sectoriales, fuentes gubernamentales en tiempo real y casos de malware activos.

---

## 🎯 Objetivos del laboratorio

- Investigar informes técnicos como el **Webroot Threat Report 2020**.
- Analizar inteligencia de amenazas por sector (salud y energía).
- Evaluar reportes y alertas emitidas por **CISA** (EE. UU.).
- Desarrollar pensamiento crítico sobre el valor y los riesgos de los informes comerciales.

---

## 📘 Estructura del análisis

### 🧩 Parte 1: Informe Webroot 2020

- **Dispositivos Android**: mayor exposición por fuentes no verificadas y fragmentación.
- **Webroot**: empresa basada en IA para protección de endpoints (hoy parte de OpenText).
- **Tendencias en ransomware**:
  - Cifrado dirigido
  - Doble extorsión (datos + rescate)
  - Modelos RaaS (Ransomware-as-a-Service)
- **Tendencias en phishing**:
  - Correos personalizados
  - SSL en sitios maliciosos
  - Multicanal: SMS, redes sociales, voz
  - Reutilización de dominios

---

### 🏥 Parte 2: Inteligencia basada en el sector

#### ▪️ Sector Salud
- **Ryuk**: ransomware propagado por RDP y phishing.
- **Emotet**: malware tipo “dropper”, con capacidades de propagación modular.

#### ⚡ Sector Energía
- **Industroyer**: diseñado para sabotear infraestructuras SCADA (energía eléctrica).
- **Havex**: RAT con funcionalidades de espionaje en sistemas industriales.

---

### 🛰️ Parte 3: Amenazas en tiempo real (CISA)

- **Grupos APT identificados**:
  - APT29 / APT28 (Rusia)
  - APT10 (China)
  - Lazarus (Corea del Norte)

- **Aviso destacado**:  
  - **APT10 (China)** atacó MSPs para robar propiedad intelectual.

- **Alerta actualizada (CISA)**:  
  - CVE-2024-22024 – Ivanti EPMM  
  - Vulnerabilidad crítica con ejecución remota. Se emitió parche el 23/05/2025.

---

## 🧠 Reflexión final

- **Desafíos del trabajo remoto**:
  - Uso de redes domésticas sin protección
  - Dispositivos personales fuera del control del SOC
  - Aumento de phishing dirigido a usuarios remotos

- **ADDTEMP Malware**:
  - Clasificación: *backdoor* y *downloader*.
  - Método de propagación: spear phishing.

- **Otras fuentes 2020**:
  - Symantec, Check Point, Palo Alto, Kaspersky, Verizon DBIR.

- **Tendencia 2021 (DBIR)**:
  - El ransomware fue el tipo de ataque más común globalmente.

- **Consideraciones sobre los informes**:
  - Útiles para planificación de defensa.
  - Importante validar fuentes y contrastar visiones.

---

## 👨‍💻 Autor

- **Nombre:** Lester Alfonso Dávila Escobedo  
- **Curso:** Cisco CyberOps – Módulo 24.1  
- **Fecha:** Junio 2025  
- **Licencia:** Creative Commons BY 4.0  
- **LinkedIn:** [linkedin.com/in/lester-alfonso-davila-escobedo-cpa](https://www.linkedin.com/in/lester-alfonso-davila-escobedo-cpa)
