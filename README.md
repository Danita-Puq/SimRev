# SimRev – Simulación de Reservorios con OPM Flow

Este repositorio contiene el material desarrollado en el marco del proyecto **“SimRev: explorando la multifuncionalidad en reservorios para la transición energética en Magallanes”**, financiado por el Concurso Interno de Proyectos Emergentes en Investigación 2023 de la Universidad de Magallanes (UMAG).

El proyecto tiene como objetivo aprovechar las capacidades de **OPM Flow** (Open Porous Media), un simulador de reservorios de código abierto, para modelar y evaluar reservorios subterráneos en distintos escenarios relevantes para la transición energética, tales como:

- Producción de hidrocarburos
- Almacenamiento geológico de CO₂
- Producción de energía geotérmica
- Aplicaciones educativas y de investigación reproducible


## ✅ Software utilizado

Los tutoriales incluidos en este repositorio fueron desarrollados y probados con las siguientes versiones:

| Software        | Versión utilizada |
|-----------------|------------------|
| **OPM Flow**    | 2024.10 |
| **ResInsight**  | 2024.12.1 |

> ⚠️ El uso de versiones diferentes podría genererar ligeras variaciones en los resultados.

---

## 📄 Contenido del repositorio

- **Manual de tutorías – OPM Flow**  
  Guía práctica orientada a estudiantes y profesionales para iniciarse en la simulación de reservorios con OPM Flow y ResInsight.

  El manual incluye:
  - Introducción a OPM Flow y ResInsight
  - Estructura de archivos `.DATA` y palabras clave
  - Casos de estudio (flujo bifásico, trifásico, tight gas, almacenamiento de CO₂)
  - Ejercicios prácticos y desafíos para reforzar el aprendizaje

 📘 [Descargar Manual de Tutorías OPM Flow UMAG](manual/Manual_de_tutorias_OPM_Flow_UMAG.pdf)

- **Archivos `.DATA` y `.RSM` de las tutorías**  
  El repositorio incluye los archivos de entrada y resultados asociados a cada tutorial.  

Cada caso cuenta con:
  - El archivo de simulación (.DATA)
  - El archivo de resultados (.RSM), generado por OPM Flow

Ambos se encuentran en la subcarpeta [`tutorias/`](tutorias/).


| Nº Tutoría | Nombre de la Tutoría                                   | Archivo `.DATA`                                      | Resultados `.RSM`                                      |
|------------|--------------------------------------------------------|-------------------------------------------------------|---------------------------------------------------------|
| 1          | Introducción a OPM Flow y ResInsight                    | [Intro_OPMFlow.DATA](tutorias/Intro_OPMFlow.DATA)     | [Intro_OPMFlow.RSM](tutorias/Intro_OPMFlow.RSM)         |
| 2          | Simulación de Petróleo-Agua                             | [Petroleo_Agua.DATA](tutorias/Petroleo_Agua.DATA)     | [Petroleo_Agua.RSM](tutorias/Petroleo_Agua.RSM)         |
| 3          | Simulación de Tres Fases                                | [Tres_Fases.DATA](tutorias/Tres_Fases.DATA)           | [Tres_Fases.RSM](tutorias/Tres_Fases.RSM)               |
| 4          | Simulación de Reservorio Tight Gas                      | [Tight_Gas.DATA](tutorias/Tight_Gas.DATA)             | [Tight_Gas.RSM](tutorias/Tight_Gas.RSM)                 |
| 5          | Simulación de Almacenamiento de CO₂                     | [CO2_Almacenamiento.DATA](tutorias/CO2_Almacenamiento.DATA) | [CO2_Almacenamiento.RSM](tutorias/CO2_Almacenamiento.RSM) |

---

## 🛠 Instalación y uso de OPM Flow

Este repositorio no contiene el código fuente del simulador.  
Para instalar **OPM Flow** y acceder a la documentación técnica oficial, se recomienda consultar el repositorio del proyecto Open Porous Media:

➡️ **Repositorio oficial del simulador OPM Flow (OPM – Open Porous Media):**  
https://github.com/OPM/opm-simulators

En ese enlace encontrarás:

- Código fuente completo
- Guías de compilación para Linux, macOS y Windows
- Issues y discusiones con la comunidad de desarrolladores

---

## ✅ Requisitos del sistema

- **Software**
  - [OPM Flow](https://opm-project.org/)
  - [ResInsight](https://resinsight.org/)
- **Sistemas operativos compatibles**
  - Linux, macOS y Windows
- **Editor recomendado**
  - [Notepad++](https://notepad-plus-plus.org/) o cualquier editor de texto plano con soporte UTF-8

---

## 🌐 Recursos adicionales

- Sitio oficial del Proyecto OPM:  
  https://opm-project.org/

- Documentación oficial de OPM Flow:  
  https://opm-project.org/?page_id=955

- ResInsight (software de visualización de modelos y resultados):  
  https://resinsight.org/

---

## 🚀 Cómo usar este repositorio

Clonar o descargar el repositorio:

```bash
git clone https://github.com/Danita-Puq/SimRev.git
