---
Fecha de creación: 2025-10-13 16:07
Fecha de Modificación: 2025-10-13 16:07
tags:
  - Latencia
  - Rendimiento
  - ArquitecturaDeSoftware
Tema: Rendimiento
---


## 📚 Idea/Concepto 
La latencia es el tiempo que transcurre entre el momento en que se realiza una solicitud y el momento en que se recibe la respuesta. Se mide en unidades de tiempo, como milisegundos (ms), y es un factor crítico en el rendimiento de los sistemas informáticos y redes. La latencia percibida por el usuario se desglosa en dos componentes: la latencia de red (que incluye la propagación, transmisión, y el tiempo de espera en routers o puntos de interconexión) y la latencia de procesamiento en el servidor (el tiempo de procesamiento de la solicitud). En sistemas distribuidos, la latencia puede incrementarse si la replicación de datos ocurre a través de una WAN o si se utiliza un diseño PA/EL, sacrificando consistencia a favor de baja latencia en la operación normal. Además, el trade-off entre latencia y throughput (transacciones por segundo) es esencial para entender el rendimiento global de un sistema. La latencia también se desglosa en componentes más específicos para aplicaciones interactivas, como la latencia de entrada, del motor de juego y de renderizado. Para optimizar el rendimiento, se deben medir métricas como P90 y P99, las cuales indican el peor caso para establecer umbrales de alerta efectivos.


## 📌 Puntos Claves (Opcional)
- **Reducción de Latencia**: Se busca minimizar la latencia utilizando técnicas como la optimización de consultas, cachés, redes de baja latencia y algoritmos eficientes.

- **Tipos de Latencia**: La latencia puede ser de red (tiempo de transmisión de datos), de procesamiento (tiempo para que el sistema procese la solicitud) y de almacenamiento (acceso a bases de datos o archivos).

- **Impacto en la Experiencia de Usuario**: La latencia afecta directamente la percepción del usuario sobre el rendimiento de la aplicación, especialmente en sistemas interactivos o en tiempo real.

- **Latencia de Red**: Depende de factores como la distancia geográfica, la congestión de la red y la calidad del servicio (QoS).

- **Optimización en Tiempo Real**: En aplicaciones en tiempo real, como videojuegos o servicios de video, la latencia debe ser minimizada para evitar una mala experiencia de usuario (por ejemplo, retrasos en la transmisión).

- **Monitorización y Control**: Herramientas de monitoreo en tiempo real pueden detectar aumentos en la latencia, lo que permite tomar acciones correctivas antes de que los usuarios noten el impacto.

## 🔗 Connections
- [[Arquitectura y Diseño]]
- [[Pruebas]]


