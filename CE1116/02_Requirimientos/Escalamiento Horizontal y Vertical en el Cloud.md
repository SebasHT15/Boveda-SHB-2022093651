---
Fecha de creación: 2025-12-06 22:40
Fecha de Modificación: 2025-12-06 22:40
tags:
  - arquitectura
  - ArquitecturaDeSoftware
  - ArquitecturaYDiseño
Tema: ArquitecturaDeSoftware
---


## 📚 Idea/Concepto 

El escalamiento horizontal (scale-out) consiste en aumentar la capacidad agregando múltiples instancias o nodos adicionales que comparten la carga mediante balanceadores de tráfico. Este enfoque mejora la disponibilidad, permite tolerancia a fallos y habilita redundancia entre zonas, lo que lo convierte en la estrategia dominante para arquitecturas distribuidas. El escalamiento vertical (scale-up) incrementa los recursos de una instancia existente —como CPU, RAM o almacenamiento—, pero está limitado por la capacidad física del servidor y puede requerir downtime para aplicar cambios. Aunque es útil para cargas monolíticas o sistemas que no permiten paralelización, suele implicar un costo mayor. En conjunto, ambos modelos permiten ajustar el rendimiento según la demanda, pero con distintas implicaciones en costo, disponibilidad y elasticidad.
## 📌 Puntos Claves (Opcional)
- Horizontal (scale-out): agregar instancias para mejorar disponibilidad y distribuir carga.
    
- Vertical (scale-up): aumentar CPU/RAM de una instancia existente; tiene límites físicos y puede requerir downtime.
    
- Scale-out suele ser más económico y favorece HA multi-zona.
    
- Scale-up útil para aplicaciones monolíticas sin paralelización.
    
- Implicaciones de costo, resiliencia y elasticidad.
