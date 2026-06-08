# WDBC-Grupo8

---
## Wisconsin Diagnostic Breast Cancer — Análisis Exploratorio de Datos

**Inteligencia Artificial · 2026 · Grupo 8**  
Luis Pinuer · Bryan Soto · Felipe Alvarado · Joaquín Barría

---

## Descripción del Proyecto

Análisis exploratorio de datos del dataset WDBC (Wisconsin Diagnostic Breast Cancer) con el objetivo de identificar patrones que permitan predecir si un tumor de mama es maligno o benigno.

**Hipótesis:** Los tumores malignos presentan mayor radio, área y concavidad que los benignos, lo que permite predecir el diagnóstico con alta precisión.

---


## Dataset

| Característica | Detalle |
|---|---|
| Fuente | UCI Machine Learning Repository |
| Registros originales | 569 |
| Registros tras limpieza | 556 |
| Features | 30 variables numéricas |
| Variable objetivo | diagnosis (M = Maligno, B = Benigno) |
| Distribución | 61.9% Benignos · 38.1% Malignos |

## Requisitos

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Cómo ejecutar

1. Clonar el repositorio
2. Instalar las dependencias
3. Abrir `Cancer.ipynb` en Jupyter Notebook o VS Code
4. Ejecutar todas las celdas en orden

---

## Contenido del Notebook

- Carga y descripción del dataset
- Limpieza y preprocesamiento
- Estadística descriptiva
- Distribución de clases
- Detección de outliers
- Distribución de variables
- Análisis de correlaciones
- Conclusiones del EDA


---
