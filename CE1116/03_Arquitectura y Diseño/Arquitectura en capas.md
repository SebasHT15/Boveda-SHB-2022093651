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
La arquitectura en capas es un modelo de diseño que estructura un sistema en niveles lógicos (layers), cada uno con responsabilidades específicas, conectados mediante interfaces bien definidas que promueven bajo acoplamiento y alto encapsulamiento.
Estas capas pueden implementarse de forma lógica o distribuirse físicamente en distintos nodos (tiers), como en arquitecturas cliente-servidor o de tres niveles.
Existen cuatro capas típicas en el desarrollo de software: Presentación (interacción con el usuario), Aplicación o Servicios (gestión de flujos y coordinación), Lógica de Negocio (procesamiento y reglas del dominio) y Acceso a Datos o Persistencia (interacción con bases de datos o almacenamiento).
Las capas pueden comunicarse mediante interacción estricta (solo entre adyacentes) o interacción suelta (saltando niveles cuando el diseño lo requiere).
Este enfoque facilita la mantenibilidad, escalabilidad y reutilización, aunque puede introducir sobrecarga de rendimiento debido a la comunicación adicional entre capas, lo que debe equilibrarse cuidadosamente según los objetivos del sistema.


## 📌 Puntos Claves (Opcional)
- Organiza el sistema en **niveles lógicos (layers)** y **niveles físicos (tiers)** con responsabilidades claramente definidas.
- Promueve **bajo acoplamiento y alto encapsulamiento**, mejorando la mantenibilidad y escalabilidad del sistema.

## 🔗 Connections
- [[Separación de responsabilidades (SoC) ]]
- [[N-capas / N-tier]]
- [[MVC / MVVM]]
