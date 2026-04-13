# ADN Barcelona: Análisis del Parque Móvil, demográfico y transición ecológica.

![Barcelona Mobility](https://img.shields.io/badge/Status-Project_Completed-success)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Data Analysis](https://img.shields.io/badge/Field-Data_Science-orange)

![BRAND](./src/main.png)

## 📌 Descripción del Proyecto

Este proyecto realiza un **Análisis Exploratorio de Datos (EDA)** exhaustivo sobre el parque automovilístico de Barcelona. El objetivo principal es desgranar la relación entre la densidad de población, el nivel de renta por distrito y la infraestructura de carga actual para determinar la viabilidad de una transición hacia una movilidad sostenible.

El estudio combina datos oficiales del Ayuntamiento de Barcelona con técnicas de *web scraping* para mapear la infraestructura de carga eléctrica de la ciudad.

## 📊 Hallazgos Principales

* **Brecha Socioeconómica:** Existe una correlación directa entre la renta per cápita y la motorización. Distritos como **Sarrià-St. Gervasi** lideran en número de vehículos y tasa de renovación.
* **Envejecimiento de la Flota:** El **48.5%** de los vehículos en Barcelona tienen más de 10 años, lo que supone un desafío crítico para las Zonas de Bajas Emisiones (ZBE).
* **Infraestructura de Carga:** La red actual de *Endolla Barcelona* está centralizada en el Eixample y zonas de alta renta, dejando a distritos periféricos como **Nou Barris** en una situación de "desierto eléctrico".
* **Dominio Térmico:** A pesar del crecimiento de los vehículos ECO, la gasolina sigue representando la mayoría absoluta de la propulsión en la ciudad.

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Python
* **Librerías de Análisis:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn, Inkscape
* **Recopilación de Datos:** BeautifulSoup / Selenium (Web Scraping de Electromaps)

## 📁 Estructura del Repositorio

* `src/notebooks/`: Jupyter Notebooks con el proceso de limpieza y análisis de datos.
* `src/data/`: Datasets utilizados (Población, Renta, Parque Móvil, Puntos de Carga).
* `src/visual/`: Gráficos generados durante el EDA.
* `src/results/`: Archivos de datos trabajados.

## 🚀 Planes de Acción Propuestos

Basado en los datos obtenidos, el proyecto sugiere:
1.  **Incentivos focalizados:** Subvenciones para renovación de vehículos en distritos de renta baja.
2.  **Reequilibrio de Red:** Priorizar la instalación de cargadores públicos en la periferia.
3.  **Carga Ultra-Rápida:** Fomentar el estándar CCS2 en centros comerciales y estaciones de servicio para mejorar la eficiencia.

---
**Autor:** [Daniel Lavía]
**Fuente de Datos:** Ayuntamiento de Barcelona & Electromaps.
