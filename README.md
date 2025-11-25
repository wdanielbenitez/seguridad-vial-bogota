# Seguridad Vial Bogotá 2024

## Objetivo del proyecto
Identificar Patrones de Riesgo, Perfiles Demográficos y Momentos Críticos, proporcionando una base analítica para la planeación de seguridad vial, basado en información de Bogotá 2024.

## Dataset usado
- <a href="https://github.com/wdanielbenitez/seguridad-vial-bogota/tree/main/data/raw/base-anuario-de-siniestralidad-2024.xlsx">base-anuario-de-siniestralidad-2024.xlsx</a>
Fuente: Datos Abiertos Bogotá (Secretaría de Movilidad)

## KPIs Principales

- **Fatalidades Totales**: Aproximadamente 585
- **Total Víctimas**: 33.000
- **Tasa Fatalidad**: 1.77%
- **Riesgo Vehículo Top 1**: Motocicleta

## Insights Clave
- **Edad Promedio	víctima mortal**:	36
- **Proporción fatalidades riesgo Hombres**: 78%
- **Vehículo con mayor fatalidad (Motocicleta)**: 68%
- **Días Críticos**: El volumen de fatalidades es significativamente más alto los Viernes y Sábados
- **Concentración Geoespacial**: Los siniestros mortales se concentran en Corredores Críticos/Puntos Negros visibles en el Mapa de Calor (Página 2)

## Herramientas
- Power BI
- Power Query
- DAX
- Mapas de Calor (Heatmap)

## Estructura
- `data/raw` - Datos fuente
- `dashboard` - Archivo principal
- `images` - Vista de cada página del archivo principal
- `images/plantillas` - Archivo Powerpoint con las plantillas utilizadas e imagenes png.
  
## Proceso
- Verificar los datos iniciales, asegurar sean consistentes y limpios de acuerdo a sus tipos de dato, formato.
- Crear columnas necesarias para el análisis.
- Crear medidas DAX.
- Generar un dashboard donde se visualice de manera eficiente la información relevante.
  
## Cómo Usar
1. Abrir el archivo .pbix en Power BI Desktop.
2. Usar los filtros de Localidad, Gravedad, Tipo día para segmentar el análisis.
3. Navegar entre las tres páginas del informe (Visión General, Análisis Geoespacial, Análisis Victima) usando los botones superiores.

## Vista Previa
![Dashboard](https://github.com/wdanielbenitez/seguridad-vial-bogota/blob/main/images/dashboard-vision-general.png)
