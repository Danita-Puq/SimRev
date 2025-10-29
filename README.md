# SimRev – Simulación de Reservorios con OPM Flow

Este repositorio contiene el material desarrollado en el marco del proyecto **“SimRev: explorando la multifuncionalidad en reservorios para la transición energética en Magallanes”**, financiado por el Concurso Interno de Proyectos Emergentes en Investigación 2023 de la Universidad de Magallanes (UMAG).

El proyecto busca aprovechar las capacidades de **OPM Flow** (Open Porous Media), un simulador de código abierto, para modelar y evaluar reservorios subterráneos en escenarios asociados a la transición energética, incluyendo:

- Producción de hidrocarburos
- Almacenamiento geológico de CO₂
- Producción de energía geotérmica
- Aplicaciones educativas y de investigación reproducible

---

## 📄 Contenido del repositorio

- **Manual de tutorías – OPM Flow**  
  Guía práctica orientada a estudiantes y profesionales para iniciarse en la simulación de reservorios con OPM Flow y ResInsight.

  Incluye:
  - Introducción a OPM Flow y ResInsight
  - Estructura de archivos `.DATA` y palabras clave
  - Casos de estudio (flujo bifásico, trifásico, tight gas, almacenamiento de CO₂)
  - Ejercicios prácticos y desafíos para reforzar el aprendizaje

 📘 [Descargar Manual de Tutorías OPM Flow UMAG](manual/Manual_de_tutorias_OPM_Flow_UMAG.pdf)

- **Archivos `.DATA` de las tutorías**  
  Casos prácticos utilizados en el manual.  
  Se encuentran en la subcarpeta [`tutorias/`](tutorias/).

| Nº Tutoría | Nombre de la Tutoría                                   | Archivo `.DATA` |
|------------|--------------------------------------------------------|------------------|
| 1          | INTRODUCCIÓN A OPM FLOW Y RESINSIGHT                    | [Intro_OPMFlow.DATA](tutorias/Intro_OPMFlow.DATA) |
| 2          | SIMULACIÓN DE PETRÓLEO-AGUA                             | [Petroleo_Agua.DATA](tutorias/Petroleo_Agua.DATA) |
| 3          | SIMULACIÓN DE TRES FASES                                | [Tres_Fases.DATA](tutorias/Tres_Fases.DATA) |
| 4          | SIMULACIÓN DE RESERVORIO TIGHT GAS                      | [Tight_Gas.DATA](tutorias/Tight_Gas.DATA) |
| 5          | SIMULACIÓN DE ALMACENAMIENTO DE CO₂                     | [CO2_Almacenamiento.DATA](tutorias/CO2_Almacenamiento.DATA) |

---

## 🛠 Instalación y uso de OPM Flow

Este repositorio no contiene el código fuente del simulador.  
Para instalar **OPM Flow** y revisar documentación técnica detallada, referirse al repositorio oficial del proyecto:

➡️ **Repositorio oficial del simulador OPM Flow (OPM – Open Porous Media):**  
https://github.com/OPM/opm-simulators

En ese enlace encontrarás:

- Código fuente completo
- Guías de compilación para Linux, macOS y Windows
- Issues y discusiones con la comunidad de desarrolladores

---

## ✅ Requisitos

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

- ResInsight (software de visualización de resultados):  
  https://resinsight.org/

---

## 🚀 Cómo usar este repositorio

Clonar o descargar el repositorio:

```bash
git clone https://github.com/Danita-Puq/SimRev.git
