# 🌐 Proyecto Intermodular - STI2

![Status](https://img.shields.io/badge/Estado-Completado-success?style=for-the-badge)
![Curso](https://img.shields.io/badge/Curso-STI2-blue?style=for-the-badge)
![Tecnología](https://img.shields.io/badge/Firewall-pfSense-f06b20?style=for-the-badge)
![VPN](https://img.shields.io/badge/VPN-OpenVPN-ea7a28?style=for-the-badge)

Repositorio del **Proyecto Intermodular** correspondiente al ciclo superior de **Sistemas de Telecomunicaciones e Informáticos (STI2)**, creado por **Brais Juárez Bastos**. 

Este proyecto documenta y detalla el diseño, despliegue y configuración de una infraestructura de red segura, incluyendo la planimetría de la instalación, normativas aplicables, configuración de enrutamiento/firewall y el despliegue de redes privadas virtuales (VPN).

---

## 📋 Índice

- [Descripción del Proyecto](#-descripción-del-proyecto)
- [Estructura del Repositorio](#-estructura-del-repositorio)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Uso de los Archivos de Configuración](#-uso-de-los-archivos-de-configuración)
- [Autor](#-autor)

---

## 📝 Descripción del Proyecto

El objetivo principal de este proyecto es simular un entorno real de telecomunicaciones, abarcando desde la fase de diseño y viabilidad hasta la configuración final de los equipos. El proyecto destaca por la implementación de un firewall robusto, segmentación de red y acceso remoto seguro.

---

## 🗂 Estructura del Repositorio

El repositorio contiene todos los documentos y archivos técnicos generados durante el proyecto. A continuación se detalla el contenido:

### 📄 Documentación Técnica
- **`PIM_Brais.pdf`**: Memoria principal y desarrollo del proyecto.
- **`PIM_Configuracion_PFSENSE.pdf`**: Documentación detallada paso a paso sobre la configuración del firewall y reglas de red.
- **`PIM_Fichas_Tecnicas.pdf`**: Especificaciones y características técnicas del hardware y software empleado.
- **`PIM_Normativa.pdf`**: Marco legal, normativas de cableado estructurado y estándares de telecomunicaciones aplicados en el diseño.
- **`PIM_PliegoCondiciones.pdf`**: Pliego de condiciones técnicas, legales y económicas.
- **`PIM_Pings.pdf`**: Batería de pruebas de conectividad y validación del despliegue en la red.

### 📐 Planos
- **`autocadPIM.dwg`**: Planos de la instalación física y despliegue de red elaborados en AutoCAD.

### ⚙️ Archivos de Configuración
- **`config-pfSenseBAO.home.arpa-20260508121849.xml`**: Archivo de copia de seguridad (backup) con la configuración íntegra desplegada en el equipo pfSense.
- **`pfSenseBAO-UDP4-1194-USER1-config.ovpn`**: Perfil de configuración de cliente OpenVPN para el Usuario 1.
- **`pfSenseBAO-UDP4-1194-USER2-config.ovpn`**: Perfil de configuración de cliente OpenVPN para el Usuario 2.

---

## 🛠 Tecnologías Utilizadas

* **pfSense**: Enrutamiento, Firewall y gestión de red.
* **OpenVPN**: Despliegue de red privada virtual para acceso remoto seguro.
* **AutoCAD**: Diseño asistido por ordenador para la planimetría de la instalación.
* **Packet Tracer / GNS3** *(si aplica)*: Simulación de la topología de red.

---

## 👤 Autor

* **Brais Juárez Bastos** - *Estudiante de Sistemas de Telecomunicaciones e Informáticos (STI2)* - [braisjrz](https://github.com/braisjrz)
