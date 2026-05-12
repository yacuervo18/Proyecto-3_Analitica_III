## Optimización de Redes Neuronales para Pronóstico de Tendencias de Salud Mental en España 

- Descripción del proyecto

Este proyecto desarrolla y compara diferentes arquitecturas de Deep Learning aplicadas al pronóstico de series de tiempo relacionadas con salud mental en España, utilizando datos de Google Trends para el término de búsqueda "ansiedad" entre 2004 y 2025.

El objetivo principal fue evaluar la capacidad predictiva de modelos recurrentes y convolucionales mediante un proceso sistemático de optimización de hiperparámetros, identificando la arquitectura con mejor capacidad de generalización fuera de muestra.

## Dataset
Fuente: Google Trends / Kaggle
Variable analizada: "ansiedad" (anxiety)
Frecuencia: mensual
Periodo: 2004 – 2025
Observaciones: 252
País: España

# IMPORTANTE
La base de datos esta adjunta en la carpeta datos. 

## Modelos evaluados
- 1. Redes recurrentes
- 2. LSTM (Long Short-Term Memory)

- GRU (Gated Recurrent Unit)
- Modelos CNN híbridos
- CNN + Dense
- CNN + LSTM
- CNN + GRU

