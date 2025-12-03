<div align="center">

#  Cyberdefenders - Lockdown Lab

</div>

<div align="center">

  [<img src="https://cyberdefenders-storage.s3.me-central-1.amazonaws.com/profile-badges/Manu.png" width="300" />](https://cyberdefenders.org/p/Manu)

  [![Cyberdefenders](https://img.shields.io/badge/Cyberdefenders-212C42?style=for-the-badge&logo=Cyberdefenders&logoColor=white)](https://cyberdefenders.org/p/Manu)
  
  ![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)
  ![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green?style=for-the-badge)
  ![Wireshark](https://img.shields.io/badge/Tool-Wireshark-informational?style=for-the-badge)
  ![VirusTotal](https://img.shields.io/badge/Tool-VirusTotal-inportant?style=for-the-badge)
  ![Volatility3](https://img.shields.io/badge/Tool-Volatility3-critical?style=for-the-badge)

</div>

##  Descripción general

Resolución del laboratorio **Lockdown** de Cyberdefenders. En el que se detalla los pasos, problemas y técnicas relevantes para la superación de este lab. Con el objetivo de adquirir conocimiento y habilidad para el desarrollo personal en la ciberseguridad, y más concretamente a la parte que más me gusta, la defensa y forense digital.

##  Descripción del Lab

Reconstruya una intrusión de múltiples etapas analizando el tráfico de red, la memoria y los artefactos de malware utilizando Wireshark, Volatility y VirusTotal, asignando los hallazgos a MITRE ATT&CK.

##  Escenario

El SOC de TechNova Systems ha detectado tráfico saliente sospechoso desde un servidor IIS público en su plataforma en la nube, actividad que sugiere un web shell drop y conexiones encubiertas a un host desconocido.

Como examinador forense, tienes tres artefactos críticos en tus manos: un PCAP que captura el tráfico inicial, una imagen completa de la memoria del servidor y una muestra de malware recuperada del disco. Reconstruye la intrusión y todas las actividades del atacante para que TechNova pueda contener la brecha y reforzar sus defensas.

##  Objetivos del laboratorio

- [x] Análisis e investigación de la captura de red
- [x] Detección de patrones anómalos.
- [x] Correlación y pivotación entre tráfico de red y memória.

### Herramientas utilizadas

- **Wireshark** - Herramienta de captura y análisis de protocolos de red.
- **Volatility3** - Herramienta de análisis de memoria volátil forense.
- **VirusTotal** - Plataforma web de escaneo para analizar y detectar malware.
