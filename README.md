# Actividad Formativa 3: Implementación y Evaluación de Filtros Digitales

## Descripción
Este repositorio contiene un cuaderno de Python (Google Colab) desarrollado para la asignatura de Señales y Sistemas. El objetivo es diseñar y evaluar filtros digitales pasa bajos, pasa altos y pasa bandas para el procesamiento de señales ruidosas.

## Contenido del Código
1. *Generación de Señales:* Se crea una señal compuesta por dos tonos (10 Hz y 100 Hz) y se le añade ruido blanco gaussiano.
2. *Diseño de Filtros:*
   - Filtro IIR Pasa Bajos (Butterworth).
   - Filtro IIR Pasa Altos (Chebyshev).
   - Filtro FIR Pasa Bandas (Ventana Hamming).
3. *Análisis:* Se grafican las señales en el dominio del tiempo y su densidad espectral de potencia (PSD) antes y después del filtrado. Además, se muestra la respuesta en frecuencia (magnitud en dB) de cada filtro diseñado.

## Herramientas
- Python 3 (Google Colab)
- NumPy
- SciPy (scipy.signal)
- Matplotlib

## Cómo ejecutar
Abre el archivo .ipynb en Google Colab y ejecuta todas las celdas. Las gráficas se generarán automáticamente.
