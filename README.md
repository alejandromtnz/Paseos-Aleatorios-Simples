# **Simulación y Análisis de Paseos Aleatorios Simples**

## Descripción del Proyecto

Este proyecto tiene como objetivo la implementación y el análisis de **paseos aleatorios simples** en dos escenarios de tiempo:

1. **Tiempo Discreto**: \( t \in \{1, 2, \dots \} \)
2. **Tiempo Continuo**: \( t \in [0, \infty) \)

Se realizará un análisis estadístico del proceso en distintos instantes de tiempo, utilizando el **método de Montecarlo** para validar las propiedades del proceso.

## Contenido

### Parte 1: Paseo Aleatorio Simple en Tiempo Discreto
Un paseo aleatorio simple es un proceso estocástico definido por:

\[
S_t = S_{t-1} + X_t, \quad t = 1, 2, 3, \dots
\]

Donde:
- \( S_t \) representa la posición en el instante \( t \)
- \( X_t \) es una variable aleatoria que puede tomar valores \( \pm 1 \) con igual probabilidad.

### Parte 2: Paseo Aleatorio Simple en Tiempo Continuo
En esta parte, el paseo aleatorio se modela para el caso de tiempo continuo. Este proceso será simulado y analizado en varios intervalos de tiempo para estudiar su comportamiento.

### Análisis Estadístico y Montecarlo
Se llevará a cabo un análisis estadístico de las posiciones del paseo aleatorio en distintos tiempos, y se aplicará el método de Montecarlo para validar las propiedades de la simulación.

## Requisitos

Para ejecutar este proyecto, necesitas tener instaladas las siguientes librerías de Python:

- `numpy`
- `matplotlib`
- `scipy`

## Resultados Esperados

El proyecto generará visualizaciones que muestran la evolución de los paseos aleatorios en función del tiempo y proporcionará un análisis sobre su comportamiento esperado, incluyendo media y varianza. Además, se validarán las propiedades del proceso utilizando simulaciones Montecarlo.
