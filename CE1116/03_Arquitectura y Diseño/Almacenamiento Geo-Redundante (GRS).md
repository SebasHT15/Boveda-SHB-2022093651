---
Fecha de creación: 2025-12-06 22:44
Fecha de Modificación: 2025-12-06 22:44
tags:
  - arquitectura
  - ArquitecturaDeSoftware
  - ArquitecturaYDiseño
Tema: ArquitecturaDeSoftware
---


## 📚 Idea/Concepto 

El Almacenamiento Geo-Redundante (GRS) replica los datos desde una región primaria hacia una región emparejada (paired region), separada típicamente por al menos 300 millas para garantizar aislamiento físico frente a desastres de gran escala. La replicación es gestionada automáticamente por la plataforma cloud y se realiza de forma asíncrona, lo que introduce una latencia natural entre regiones y la posibilidad de perder los últimos cambios en caso de failover. GRS es el modelo recomendado para estrategias de recuperación ante desastres (DR), ya que permite mantener la continuidad operativa incluso cuando una región completa queda inhabilitada. Aunque ofrece la mayor resiliencia geográfica disponible, requiere considerar los efectos de la latencia interregional y las políticas de conmutación por falla proporcionadas por el proveedor.
## 📌 Puntos Claves (Opcional)
- Replica datos hacia una región emparejada a 300+ millas.
    
- Replicación asíncrona gestionada por la plataforma.
    
- Diseñado para recuperación ante desastres (DR).
    
- Mantiene continuidad operativa si toda una región falla.
    
- Puede perder datos recientes en failover debido a asincronía.
