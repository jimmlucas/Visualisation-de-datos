
# PEC 2 - Visualización de Datos 

Este repositorio contiene las tres visualizaciones desarrolladas para la **PEC 2**, donde se aplican distintas técnicas gráficas.
Cada visualización se ha generado en **Python (Plotly)** a partir de **fuentes de datos abiertas**, y se publica mediante **GitHub Pages** para su acceso público.  

El objetivo principal es explorar la relación entre técnica de visualización, estructura de datos, utilizando tres enfoques complementarios:

1. **Gráfico de dispersión (Scatterplot)**  
2. **Gráfico de pendientes (Slope chart)**  
3. **Diagrama de rosa / Gráfico polar (Rose chart)**  


## Visualizaciones disponibles

### 1. Scatterplot — PIB per cápita vs Esperanza de vida (2023)
**URL:** [Ver visualización](https://jimmlucas.github.io/Visualisation-de-datos/scatter.html)  
**Fuente:** World Bank — *World Development Indicators (WDI)*  
**Indicadores:**  
- PIB per cápita (NY.GDP.PCAP.CD)  
- Esperanza de vida (SP.DYN.LE00.IN)  
**Descripción:**  
Representa la relación entre el nivel económico y la esperanza de vida por país en 2023.  
Permite observar la correlación positiva entre riqueza y salud global.  


### 2. Slope Chart — Mortalidad infantil (2010 vs 2020)
**URL:** [Ver visualización](https://jimmlucas.github.io/Visualisation-de-datos/slope_mortality_2010_2020.html)  
**Fuente:** World Bank — *SP.DYN.IMRT.IN (Infant Mortality Rate)*  
**Descripción:**  
Muestra la evolución de la tasa de mortalidad infantil en el mundo entre 2010 y 2020.  
Cada línea representa un país; la pendiente indica mejora o empeoramiento.  
La mayoría de países presentan una disminución, destacando avances globales en salud infantil.  


### 3. Rose Chart — Vacunaciones COVID-19 por mes (España, 2021–2023)
**URL:** [Ver visualización](https://jimmlucas.github.io/Visualisation-de-datos/rose_vaccinations.html)  
**Fuente:** Our World in Data — *COVID-19 Vaccination Dataset*  
**Descripción:**  
Distribución mensual de dosis administradas de vacunas COVID-19 en España (2021–2023).  
Cada sector representa un mes y el radio indica el porcentaje del total.  
Permite identificar los meses de mayor intensidad en la campaña de vacunación, con picos en verano (junio–julio).  

## Herramientas empleadas
- **Python 3.11**  
- **Pandas 2.2.3**  
- **Plotly 6.4.0**  
- **GitHub Pages** (con el fin de publicación web)


## Licencias y fuentes de obtencion de datos
Todos los datos empleados son de **acceso abierto** y se distribuyen bajo licencias **CC BY 4.0**:

- [World Bank Open Data](https://data.worldbank.org/)  
- [Our World in Data](https://ourworldindata.org/covid-vaccinations)  
