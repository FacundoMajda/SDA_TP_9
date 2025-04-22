# Detector de Toxicidad

## Descripción

Una aplicación web que identifica contenido tóxico en textos, Utiliza TensorFlow.js y un modelo pre-entrenado para analizar si un texto contiene elementos como insultos, amenazas o contenido explícito.

## Características

- Análisis en tiempo real de texto ingresado por el usuario
- Detección de 7 categorías de toxicidad (insultos, amenazas, toxicidad general, etc.)
- Visualización del porcentaje de probabilidad para cada categoría

## Cómo funciona

El sistema carga un modelo de IA pre-entrenado directamente en el navegador. Cuando el usuario ingresa un texto, este es procesado por el modelo que devuelve la probabilidad de toxicidad para cada categoría.

## Tecnologías utilizadas

- HTML, CSS y JavaScript para la interfaz de usuario
- TensorFlow.js para ejecutar el modelo de IA en el navegador
- Modelo de toxicidad pre-entrenado (@tensorflow-models/toxicity)

## Cómo usar

1. Abre el archivo index.html en tu navegador
2. Espera a que el modelo termine de cargar
3. Escribe el texto que quieres analizar en el campo de texto
4. Haz clic en "Analizar"
5. Observa los resultados que muestran la probabilidad de toxicidad por categoría
