---
Fecha de creación: 2025-11-06 17:45
Fecha de Modificación: 2025-11-06 17:45
tags:
  - arquitectura
  - ArquitecturaDeSoftware
  - ArquitecturaYDiseño
Tema: ArquitecturaDeSoftware
---


## 📚 Idea/Concepto 

La cohesión en desarrollo de software es el grado en que los elementos de un módulo o clase colaboran para cumplir una única preocupación o rol claramente definido, agrupando las operaciones que cambian juntas y comparten un propósito común. La alta cohesión surge al aplicar el principio de Separación de Preocupaciones (SoC) y se relaciona directamente con el patrón Information Expert, ya que el módulo cohesivo concentra la información y el comportamiento necesarios para cumplir su responsabilidad sin depender de otros. Este diseño reduce la complejidad, facilita la reutilización del código en nuevos contextos y actúa como un criterio central para evaluar la efectividad de la modularización. Por el contrario, la baja cohesión genera módulos que mezclan responsabilidades, aumentando el acoplamiento, la duplicación y la probabilidad de cambios dispersos o contradictorios en el sistema.
## 📌 Puntos Claves (Opcional)
- Mide qué tan bien los elementos de un módulo **trabajan juntos hacia una única responsabilidad o preocupación**.
- La **alta cohesión** mejora la mantenibilidad, evita _code smells_ como _Shotgun Surgery_, y refuerza la modularidad.

## 🔗 Connections
- [[ Single Responsibility Principle (SRP)]]
- [[Modularidad]]

