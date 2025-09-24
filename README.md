# Repositorio: Modelos-WRF

El repositorio **Modelos-WRF** reúne la implementación, documentación y resultados de diferentes configuraciones del modelo **WRF (Weather Research and Forecasting)**, adaptado para generar pronósticos climáticos regionales sobre el territorio peruano. Estos sistemas de predicción regional buscan capturar la complejidad atmosférica de la región andina y amazónica, mejorando la representación espacial y temporal de variables clave para la gestión climática, meteorológica e hidrológica.  

En este repositorio se presentan tres sistemas principales, cada uno con distinta fuente global de inicialización, resolución espacial y horizonte temporal de pronóstico:  

---

## Modelo regional subestacional **WRF-GEFS**

- **Fuente global**: **GEFS** (Global Ensemble Forecast System, NOAA).  
  Sistema de predicción global por conjuntos, compuesto por 31 miembros, que permite estimar la incertidumbre de los pronósticos atmosféricos y climáticos. Proporciona proyecciones hasta 35 días y es ampliamente usado en aplicaciones de escala subestacional a estacional.  

- **Configuración regional**:  
  - Resolución espacial: **8 km**  
  - Cobertura: **Perú**  
  - Frecuencia: **semanal (miércoles)**  
  - Horizonte: **35 días** (promedio de los 31 miembros)  

- **Productos generados**:  
  - Anomalías de **precipitación**  
  - Anomalías de **temperatura media, máxima y mínima**  

Este sistema permite disponer de información actualizada cada semana para la toma de decisiones en sectores sensibles al clima, como agricultura, gestión de recursos hídricos y gestión de riesgos.  

---

## Modelo regional mensual **WRF-CFSv2**

- **Fuente global**: **CFSv2** (Climate Forecast System, versión 2 – NCEP/NOAA).  
  Modelo acoplado atmósfera-océano que provee predicciones estacionales globales. Está diseñado para capturar fenómenos de variabilidad climática como **El Niño-Oscilación del Sur (ENOS)** y su impacto regional.  

- **Configuración regional**:  
  - Resolución espacial: **16 km**  
  - Cobertura: **Perú**  
  - Frecuencia: **mensual**  
  - Horizonte: **6 meses**  

- **Productos generados**:  
  - Anomalías mensuales de **precipitación**  
  - Anomalías mensuales de **temperatura media, máxima y mínima**  

Este sistema ofrece una visión consolidada de la evolución climática a mediano plazo.  

---

## Modelo regional mensual **WRF-ECMWF**

- **Fuente global**: **ECMWF System 5 (S5)**.  
  El sistema estacional del ECMWF es uno de los referentes globales en predicción climática. Integra observaciones atmosféricas, oceánicas y de superficie terrestre, con alta habilidad predictiva en diversas regiones del mundo.  

- **Configuración regional**:  
  - Resolución espacial: **10 km**  
  - Cobertura: **Perú**  
  - Frecuencia: **mensual**  
  - Horizonte: **7 meses**  

- **Productos generados**:  
  - Anomalías mensuales de **precipitación**  
  - Anomalías mensuales de **temperatura media, máxima y mínima**  

Este sistema brinda información de alta calidad para el seguimiento y anticipación de fenómenos climáticos de escala estacional.  

---

##  Objetivo del repositorio

El propósito de **Modelos-WRF** es centralizar los **scripts, configuraciones y resultados** derivados de estas simulaciones regionales, contribuyendo al desarrollo de servicios climáticos en el Perú.  

La combinación de estas tres fuentes globales (GEFS, CFSv2, ECMWF-S5) permite:  

- Mejorar la representación espacial del clima en zonas de topografía compleja.  
- Generar predicciones subestacionales y estacionales ajustados a la realidad local.  
- Brindar productos operativos para apoyar la planificación y la toma de decisiones estratégicas.  
