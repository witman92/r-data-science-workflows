# Analítica de horas-hombre en operación industrial (R)

Análisis exploratorio y proyección presupuestaria del consumo de **horas-hombre** de personal externo en una planta de alimentos durante 12 meses (2024), por **planta y centro de costo**.

▶️ [Video demostrativo del código](https://drive.google.com/file/d/1e6XYRqI8mHV2K5f-6_LL6khYOSd0hHHi/view?usp=sharing)

## Qué incluye
- **Caracterización de patrones de consumo**: distribución y densidad de horas normales y extra (simetría, curtosis, subgrupos).
- **Análisis de correlación múltiple** con `corrplot` y `GGally`, encapsulado en una **función S3**.
- **Transformación logarítmica** `log(1 + x)` para normalizar distribuciones con ceros.
- **Presupuesto del próximo año**: proyección a 12 meses de horas normales y extra por centro de costo y planta, más estimación de necesidad de horas extra.

## Estructura
```
horas_hombre_analysis.Rmd     # Análisis completo en R Markdown
datos_horas_hombre.xlsx       # Dataset
```

**Stack:** R · R Markdown · readxl · corrplot · GGally · ggplot2
