---
Fecha de creación: 2025-08-30 18:24
Fecha de Modificación: 2025-08-30 18:24
tags:
  - arquitectura
Tema: inteligencia-artificial
---


## 📚 Idea/Concepto 
La ventana de contexto es el segmento de tokens que un modelo puede procesar de forma simultánea mediante self-attention para predecir el siguiente token. Su tamaño influye directamente en la coherencia y el costo de procesamiento, ya que la atención tiene complejidad cuadrática. Para preservar el orden de los tokens se usa Positional Encoding, y dentro de la ventana el modelo genera embeddings contextuales, adaptando el significado de cada token según su entorno.

## 📌 Puntos Claves (Opcional)
- Limita cuántas palabras o tokens puede procesar un modelo en una sola interacción.
- Modelos más avanzados tienen ventanas de contexto mucho más grandes.
- Afecta la calidad y coherencia de las respuestas en conversaciones largas.

## 🔗 Connections
- [[Large Language Models (LLMs)]]
- [[Mecanismo de atención en Transformers]]
