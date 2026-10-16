# Quantile Regression Forest · intervalos e incertidumbre

Cuaderno exploratorio de regresión por cuantiles. Contiene dos líneas de análisis: un ejemplo de temperatura y un análisis de delitos denunciados por distrito fiscal en Perú, con preparación de tablas anuales, mapas y predicciones de intervalos `p10`, `p50` y `p90`.

## Reproducibilidad

Abrir `Quantile_Regression_Forest_(QRF).ipynb` en Jupyter o Colab. El cuaderno requiere `pandas`, `numpy`, `scikit-learn`, `quantile-forest` o `skranger`, `geopandas`, `matplotlib`, `seaborn` y `plotly`. Parte del análisis descarga un GeoJSON externo y otra parte espera CSV de delitos que **no están incluidos**. Las secciones redefinen variables; ejecutarlas en orden y registrar qué dataset corresponde a cada resultado.

Los intervalos reflejan la muestra y supuestos usados. Antes de comunicar un pronóstico de delitos hay que documentar la fuente oficial, cobertura, subregistro, cambios de metodología y evaluación temporal fuera de muestra. No interpretar una predicción distrital como probabilidad de delito individual.
