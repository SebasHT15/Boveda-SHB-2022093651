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
La arquitectura event driven es un modelo de diseño en el que el sistema se estructura alrededor de la producción, transmisión y reacción a eventos, entendidos como hechos inmutables que representan acciones ya ocurridas. Los componentes se comunican mediante un mecanismo Publish/Subscribe, lo que permite un bajo acoplamiento y alta escalabilidad. La distribución puede seguir una topología de Broker, basada en la difusión de eventos, o una de Mediador, centrada en la orquestación del flujo. Este enfoque suele operar bajo consistencia eventual, priorizando la baja latencia y la resiliencia. Los consumidores mantienen su propio estado local y reaccionan de forma asíncrona, lo que introduce complejidad en la sincronización. Tecnologías como Apache Kafka, RabbitMQ o Azure Event Hubs facilitan la implementación de este modelo, mientras que el registro de eventos (event log) proporciona trazabilidad, auditoría y soporte para patrones como Event Sourcing.

## 📌 Puntos Claves (Opcional)
- Estructura el sistema en torno a la **generación y respuesta a eventos**, permitiendo comunicación asíncrona entre componentes.
- Favorece el **desacoplamiento** y la **escalabilidad**, aunque introduce desafíos de consistencia y coordinación.
## 🔗 Connections
- [[ MVC / MVVM]]
- [[Consistencia eventual]]

