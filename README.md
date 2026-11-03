# Análisis Agrícola – Perú 2025

Análisis exploratorio de datos agrícolas de Perú usando Python (Pandas, Matplotlib y Seaborn).

## Qué se analizó

- Producción total por cultivo
- Ingresos totales por región
- Producción mensual durante el año
- Producción promedio según tipo de riego
- Porcentaje de registros rentables

## Archivos

- `AnalisisAgricola.ipynb`: notebook con el análisis completo
- `AgriculturaPeru.csv`: dataset original
- `AnalisisAgricolaLimpio.csv`: dataset limpio
- `DATASET_AGRICOLA_LIMPIO.xlsx`: dataset limpio en Excel
- `graficos/`: gráficos generados

## Limpieza de datos

- Se eliminaron filas con datos faltantes en producción, precio e ingresos.
- Se convirtió la columna `Fecha` a formato fecha.
- Se crearon las columnas `Mes` y `Rentabilidad` (ingresos − costo de producción).

## Cómo ejecutarlo

```bash
git clone https://github.com/frankboz/Python-DatasetAgricola.git
cd Python-DatasetAgricola
pip install pandas matplotlib seaborn jupyter
jupyter notebook AnalisisAgricola.ipynb
```

## Autor

Frank – [GitHub](https://github.com/frankboz)
