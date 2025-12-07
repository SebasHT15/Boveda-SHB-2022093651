---
Fecha de creación: 2025-12-06 22:43
Fecha de Modificación: 2025-12-06 22:43
tags:
  - arquitectura
  - ArquitecturaDeSoftware
  - ArquitecturaYDiseño
Tema: ArquitecturaDeSoftware
---


## 📚 Idea/Concepto 

El Almacenamiento Redundante Localmente (LRS) replica los datos dentro de un único centro de datos o una sola zona de disponibilidad, manteniendo varias copias —normalmente tres— para proteger contra fallas de discos, servidores y racks. Este modelo garantiza durabilidad dentro de la misma ubicación física, pero no ofrece protección frente a interrupciones que afecten toda la zona o región, lo cual requiere opciones multizona como ZRS o georredundantes como GRS. LRS es la alternativa de redundancia más económica, ya que limita la replicación al ámbito local, siendo adecuado para cargas de trabajo cuya resiliencia no exige continuidad ante desastres de mayor escala.
## 📌 Puntos Claves (Opcional)
- Replica datos dentro de un único centro de datos/una zona.
    
- Protege contra fallas de discos, servidores y racks.
    
- Normalmente 3 copias locales.
    
- Es la opción más económica.
    
- No protege contra fallas multizona o regionales.
