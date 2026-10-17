## trabajo-parcial-geocomputacion
Evaluación del impacto de El Niño Costero 2017 en Trujillo mediante geocomputación.
**Evaluación del impacto de El Niño Costero (2017) en la provincia de Trujillo mediante geocomputación**

**Descripción del proyecto**

Este trabajo evalúa la relación entre la precipitación extrema y las áreas potencialmente afectadas por inundaciones durante el evento de El Niño Costero de 2017 en la provincia de Trujillo, región La Libertad, Perú, mediante herramientas de geocomputación y análisis de datos geoespaciales.

**Objetivo general**

Evaluar la relación entre la precipitación diaria durante El Niño Costero de 2017 y la extensión de las superficies potencialmente afectadas por inundaciones en la provincia de Trujillo, integrando datos de precipitación satelital y observaciones de radar.

**Área y periodo de estudio**

- **Área de estudio:** provincia de Trujillo, La Libertad, Perú.
- **Periodo de análisis:** febrero a abril de 2017.

**Datos utilizados**

- **PISCOp_d v3.0 (SENAMHI):** datos de precipitación diaria.
- **GPM IMERG (NASA):** estimaciones satelitales de precipitación.
- **Sentinel-1 RTC:** imágenes de radar utilizadas para explorar cambios en la retrodispersión VV antes y después del evento.

**Metodología**

1. Descarga y preparación del límite geográfico de la provincia de Trujillo.
2. Consulta y selección de imágenes Sentinel-1 RTC para dos periodos: antes y después del inicio del evento.
3. Recorte y visualización de la retrodispersión VV en el área de estudio.
4. Preparación y comparación temporal de las series de precipitación de PISCOp_d e IMERG.
5. Exploración de la relación entre la precipitación y las posibles áreas afectadas.

**Herramientas utilizadas**

- Python y Google Colab.
- GeoPandas y Rioxarray.
- PySTAC Client y Microsoft Planetary Computer.
- Xarray, Pandas y Matplotlib.
- Google Earth Engine, para la configuración inicial del entorno cuando corresponda.

**Integrantes**

- Javier Esparza Escudero
- Jimena Tamariz


**Archivo principal**

El notebook de Google Colab contiene el código de procesamiento, análisis y visualización de los datos utilizados en el proyecto.
