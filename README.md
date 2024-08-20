# Proyecto de Clusterización de Pacientes - Trabajo Final

Este proyecto tiene como objetivo agrupar pacientes según sus diagnósticos y otros factores relevantes utilizando técnicas de **Machine Learning**, específicamente el algoritmo de **KMeans**. La clusterización permite identificar patrones en los datos de salud que pueden ser útiles para mejorar la atención médica y la gestión de los recursos.

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Archivos y Estructura del Proyecto](#archivos-y-estructura-del-proyecto)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Resultados](#resultados)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)
- [Contacto](#contacto)

## Descripción del Proyecto

Este proyecto toma un conjunto de datos de pacientes y utiliza el algoritmo de KMeans para agrupar a los pacientes en clusters basados en sus diagnósticos y otras características relevantes como la edad y el sexo. El análisis de clusters ayuda a identificar grupos de pacientes con patrones de salud similares, lo cual puede ser utilizado para optimizar los tratamientos médicos y las intervenciones.

## Archivos y Estructura del Proyecto

- `DATA_SIS_Consolidada_Preproceso.csv`: Conjunto de datos preprocesados utilizado para la clusterización.
- `cluster_pacientes.py`: Script principal que realiza la clusterización y visualización.
- `README.md`: Este archivo README que describe el proyecto.
- `requirements.txt`: Archivo con las dependencias necesarias para ejecutar el proyecto.

## Requisitos

Este proyecto requiere Python 3.7 o superior. Las dependencias necesarias están listadas en el archivo `requirements.txt`.

### Principales librerías utilizadas:

- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## Instalación

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu_usuario/clusterizacion-pacientes.git
   cd clusterizacion-pacientes
