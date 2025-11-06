---
Fecha de creación: 2025-11-06 17:40
Fecha de Modificación: 2025-11-06 17:40
tags:
  - arquitectura
  - ArquitecturaDeSoftware
  - ArquitecturaYDiseño
Tema: ArquitecturaDeSoftware
---


## 📚 Idea/Concepto 
En las arquitecturas Event Driven, el Broker es un intermediario que gestiona la publicación y distribución asíncrona de eventos bajo el modelo Publish/Subscribe (Pub/Sub), promoviendo un bajo acoplamiento basado en el principio de Separación de Responsabilidades (SoC). Existen dos tipos principales: el Message Broker, con entrega transitoria de mensajes (p. ej., RabbitMQ), y las plataformas de Event Streaming, que mantienen un registro inmutable y reproducible de eventos (p. ej., Kafka). En este esquema, los receptores asumen la gestión de su propio estado local, lo que aumenta la complejidad y requiere que sean idempotentes para garantizar la coherencia. Aunque este modelo prioriza la disponibilidad y la baja latencia (consistencia eventual), introduce desafíos de trazabilidad y una mayor carga cognitiva al distribuir la lógica entre múltiples componentes, lo que demanda estrategias avanzadas de observabilidad y monitoreo de flujos.

## 📌 Puntos Claves (Opcional)
- Actúa como **intermediario** en el modelo **Publish/Subscribe**, distribuyendo eventos entre productores y consumidores.
- Existen dos variantes principales: **Message Broker** (mensajería transitoria) y **Event Streaming** (registro inmutable y reproducible).

## 🔗 Connections
- [[ Message Broker]]
- [[Event Streaming (Kafka, etc.)]]


