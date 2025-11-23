# Dingtian-16relay-Venus-OS-Raspberry-Pi-
Este repositorio contiene la documentación, configuración y archivos necesarios para integrar un módulo Dingtian DT-R016 (16 relés + 16 entradas) con una Raspberry Pi con Venus OS, utilizando MQTT y el servicio external-devices.


Características principales

Control completo de 16 relés desde Venus OS GUI v2
Lectura de 16 entradas digitales
Integración nativa mediante D-Bus
Uso del broker MQTT interno (puerto 1884)
Compatibilidad con Victron Cerbo GX, Ekrano GX y Raspberry Pi
Menús personalizados con iconos GUI v2
Manual detallado y archivo optionsSet listo para usar





Control avanzado de relés, entradas digitales y sensores en Venus OS GUI v2




📖 Descripción general

Este repositorio contiene la configuración, scripts y documentación necesarios para integrar un módulo Dingtian DT-R016 (16 relés + 16 entradas) en una Raspberry Pi con Venus OS 3.66, utilizando el servicio external-devices (drtinaz).

El objetivo es que los relés y sensores del Dingtian se muestren en D-Bus y puedan controlarse desde la GUI v2 de Victron (Ekrano, Cerbo GX o Raspberry Pi).

Incluye:

Configuración completa de MQTT

Fichero optionsSet preparado para GUI v2

Scripts de instalación

Diagnóstico y herramientas de prueba

Manual detallado de funcionamiento

🚀 Características

✔ Integración completa con Venus OS GUI v2
✔ Control de 16 relés independientes
✔ Lectura de 16 entradas digitales
✔ Sin necesidad de Node-RED
✔ Compatible con Raspberry Pi 3/4/5
✔ Configuración persistente incluso tras actualizaciones
✔ Basado en MQTT (broker interno 1884)

🛠️ Requisitos
Componente	Versión
Módulo Dingtian	DT-R016 (16CH)
Raspberry Pi	3B / 4B / 5
Firmware Venus OS	≥ 3.66
Servicio	external-devices (drtinaz)  https://github.com/drtinaz/external-devices
