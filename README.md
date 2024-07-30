# Análisis de Sensibilidad e Incertidumbre del Modelo SIR

Este repositorio contiene los archivos y el informe del proyecto realizado para la práctica de control y análisis de sensibilidad e incertidumbre sobre un sistema dinámico no lineal con entrada, específicamente un modelo SIR (Susceptibles-Infectados-Recuperados). A continuación, se detallan los contenidos del repositorio y las secciones del informe en formato IMRAD.

## Contenidos del Repositorio

### Informe en Formato IMRAD

- **Archivo Live Script**: `Trabajo2_SL_Final.mlx`
  - Contiene los resultados del trabajo presentados en formato IMRAD. Desde este archivo se ejecutan y presentan los resultados de las diferentes pruebas.

### Control de Realimentación del Estado

- **Archivo de Simulink**: Contiene el modelo de Simulink utilizado para el control de realimentación del estado.

### Análisis de Sensibilidad e Incertidumbre

- **Archivo de Simulink**: Contiene el modelo de Simulink utilizado para el análisis de sensibilidad.
- **Archivo de Información**: Contiene información adicional y detalles del análisis de sensibilidad.
- **Archivo GSUA**: Contiene el código de MATLAB para el análisis de sensibilidad e incertidumbre utilizando la herramienta GSUA.

## Secciones del Informe IMRAD

### Introducción

Se presenta una breve introducción al problema abordado, el modelo SIR y la importancia del análisis de sensibilidad e incertidumbre en sistemas dinámicos no lineales.

### Modelo Matemático y Breve Descripción

Se describe el modelo matemático del sistema SIR, incluyendo las variables de entrada, salida y estado, así como los parámetros del modelo.

### Hipótesis

Se presentan las hipótesis planteadas para el análisis y control del modelo SIR.

### Métodos

- **Modelo Verificado en Simulink**: Se incluye la verificación del modelo SIR en Simulink, el cual es utilizado como insumo para el análisis posterior.
- **Pruebas y Simulaciones**: Se detallan los cálculos y modelos matemáticos utilizados en cada prueba y simulación, haciendo énfasis en los aspectos matemáticos y el uso del software MATLAB y Simulink.
- **Resumen de Pasos**: Se resume el procedimiento seguido para llevar a cabo el análisis de sensibilidad e incertidumbre.

### Resultados

- **Control Lineal por Realimentación del Estado**: Se diseñó y simuló un control lineal de asignación de polos por realimentación del estado para un punto de equilibrio seleccionado. Incluye:
  - Trazado de la curva de linealidad.
  - Selección de un punto de equilibrio de interés.
  - Linealización en el punto de operación.
  - Comparación entre la aproximación lineal y el modelo no lineal.
  - Análisis de controlabilidad del modelo lineal.
  - Diseño del controlador y simulación del sistema en lazo cerrado.
  - Análisis de la respuesta del sistema ante perturbaciones en la entrada.

- **Análisis de Incertidumbre**: Programa y gráficos del análisis de incertidumbre de la salida del proceso con el controlador y las perturbaciones.

- **Análisis de Sensibilidad Escalar**: Gráficos del análisis de sensibilidad escalar para clasificar los parámetros del modelo de los más a los menos sensibles utilizando la herramienta GSUA.

### Discusión

Interpretación de los resultados obtenidos en el análisis de sensibilidad e incertidumbre, así como en el diseño del control lineal por realimentación del estado.
