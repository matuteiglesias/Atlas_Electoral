# Atlas Electoral

## Descripción del Proyecto

El proyecto **Atlas Electoral** está diseñado para analizar y visualizar datos electorales en Argentina, integrando circuitos electorales con información demográfica y generando poblaciones sintéticas para análisis estadísticos. Este repositorio es una herramienta clave para investigadores, analistas de políticas públicas y especialistas en datos interesados en explorar comportamientos electorales y patrones socioeconómicos a través de datos geoespaciales.

## Características Principales

- **Análisis Geoespacial:** Mapeo de circuitos electorales y análisis basado en fronteras geográficas.
- **Generación de Poblaciones Sintéticas:** Creación de datos simulados para representar dinámicas de población y comportamiento electoral.
- **Modelos de Aprendizaje Automático:** Entrenamiento de modelos para predecir resultados electorales y analizar tendencias demográficas.
- **Integración de Datos:** Combinación de datos electorales, censales y de encuestas para crear datasets completos.

## Estructura del Repositorio

- `data/`: Contiene los datasets utilizados para el análisis (circuitos electorales, datos censales, etc.).
- `notebooks/`: Notebooks Jupyter que documentan los procesos de análisis, generación de datos sintéticos y visualización.
- `scripts/`: Scripts en Python para el procesamiento y análisis de datos, como `satellite.py`.
- `results/`: Carpeta opcional para almacenar resultados generados (modelos entrenados, visualizaciones, etc.).
- `README.md`: Este documento, con instrucciones detalladas del proyecto.

## Instalación

### Requisitos Previos
- **Python 3.8+**
- **Bibliotecas necesarias:**
  - pandas
  - geopandas
  - matplotlib
  - scikit-learn
  - folium (para mapas interactivos)
  - jupyterlab (opcional, para ejecutar notebooks)

### Instrucciones

1. Clona el repositorio:
   ```bash
   git clone https://github.com/matuteiglesias/Atlas_Electoral.git
   cd Atlas_Electoral
