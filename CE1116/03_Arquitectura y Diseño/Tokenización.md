---
Fecha de creación: 2025-08-30 18:25
Fecha de Modificación: 2025-08-30 18:25
tags:
  - arquitectura
Tema: inteligencia-artificial
---


## 📚 Idea/Concepto 

La tokenización es el proceso de preprocesamiento que divide el texto en tokens —generalmente subpalabras producidas por algoritmos como Byte-Pair Encoding (BPE) a partir de un vocabulario predefinido— que luego se transforman en embeddings numéricos. Estos embeddings se combinan con codificaciones posicionales y se utilizan en el mecanismo de autoatención, permitiendo capturar el orden y las dependencias contextuales. La granularidad de los tokens influye directamente en la ventana de contexto y el manejo de palabras fuera de vocabulario (OOV), aspectos fundamentales en el diseño de LLMs.

## 📌 Puntos Claves (Opcional)
- Convierte texto en unidades que el modelo puede interpretar.
- Dependiendo del enfoque, un token puede ser una palabra completa o una subpalabra.
- Es el primer paso antes de generar embeddings y aplicar el mecanismo de atención.

## 🔗 Connections
- [[Embeddings]]
- [[Ventana de Contexto]]
- [[Large Language Models (LLMs)]]
