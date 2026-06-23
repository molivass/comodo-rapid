<p align="center">
  <img src="misc/comodo-rapid_logo.svg" width="500" alt="Logo de COMODO Rapid">
</p>

# COMODO Rapid

Programa desarrollado en **RAPID** para el robot ABB IRB 1090. Este módulo permite la integración del robot en el proyecto COMODO, enviando su estado y recibiendo órdenes de movimiento a través del PLC.

Desarrollado en **ABB RobotStudio**, el programa maneja la comunicación con el PLC mediante tramas de 64 bits y la ejecución de movimientos.

## Estructura del Proyecto

* **`/rapid_modules`**: Módulos RAPID que componen el programa del robot (main, subrutinas).
* **`/robotstudio_project`**: Archivos del proyecto de RobotStudio.

## Instalación

1. Clona este repositorio.
2. Abre el proyecto en RobotStudio y sincronízalo con el robot real.
3. Carga el programa en la controladora.

> **Nota**: Diseñado para el robot **ABB IRB 1090** con controladora **OmniCore E10**.

