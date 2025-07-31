# Procesamiento de Imágenes Satelitales (Sentinel-2)

Este proyecto implementa un flujo completo de **procesamiento de imágenes satelitales en formato RAW** procedentes de la plataforma **Copernicus Data Space Ecosystem**, utilizando Python y Google Colab.

El objetivo principal es **transformar imágenes satelitales sin procesar** en productos listos para análisis medioambientales, agrícolas o de gestión de desastres, aplicando técnicas de corrección, filtrado y análisis espectral.

---

## 📌 Contenidos

- **Selección de imágenes Sentinel-2**  
  Descarga y preparación de datos en formato JP2 (JPEG2000) de diferentes bandas espectrales.

- **Apertura y visualización**  
  Uso de `rasterio`, `matplotlib` y `numpy` para visualizar bandas en escala de grises y composiciones RGB.

- **Validación y metadatos**  
  Verificación de resolución, sistema de referencia y consistencia de datos.

- **Identificación y corrección de errores**
  - Valores `nodata`
  - Valores fuera de rango
  - Errores de sensor
  - Distorsiones geométricas

- **Corrección geográfica**
  - Georreferenciación y reproyección a distintos sistemas de coordenadas.

- **Cálculo de índices de vegetación**
  - **RVI** (Ratio Vegetation Index)
  - **NDVI** (Normalized Difference Vegetation Index)
  - **SAVI** (Soil Adjusted Vegetation Index)
  - **TVI** (Transformed Vegetation Index)
  - **BAI** (Burned Area Index)

- **Transformaciones y análisis de imagen**
  - Histogramas y ecualización
  - Expansión lineal y corte de colas
  - Filtros (suavizado, realce, Sobel…)
  - Escalado y enmascaramiento

---

## 🛠 Herramientas utilizadas

- **Python 3**
- Librerías:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `rasterio`
- **Google Colab** (entorno de ejecución)
