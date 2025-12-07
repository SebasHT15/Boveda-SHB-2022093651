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

El Almacenamiento Redundante en Zona (ZRS) replica automáticamente los datos entre múltiples zonas de disponibilidad dentro de una misma región, donde cada zona es una unidad físicamente independiente con energía, enfriamiento y red aislados. Este modelo, disponible únicamente en regiones con tres o más zonas, ofrece resiliencia frente a la pérdida completa de una de ellas, ya que las réplicas permanecen accesibles desde las zonas restantes. ZRS se aplica a servicios que soportan redundancia multizona —como ciertas cuentas de almacenamiento y bases de datos— y su replicación es gestionada completamente por la plataforma. Aunque proporciona alta disponibilidad regional, sigue siendo vulnerable a fallas que afecten a la región completa, por lo que no sustituye a modelos de recuperación geográfica como GRS.
## 📌 Puntos Claves (Opcional)
- Replica datos entre múltiples zonas de disponibilidad dentro de la misma región.
    
- Alta resiliencia ante falla de una zona completa.
    
- Requiere que la región tenga ≥3 zonas.
    
- Replicación automática gestionada por la plataforma.
    
- Aún vulnerable a fallas regionales completas.

