---
Fecha de creación: 2025-11-06 17:46
Fecha de Modificación: 2025-11-06 17:46
tags:
  - arquitectura
  - ArquitecturaDeSoftware
  - ArquitecturaYDiseño
Tema: ArquitecturaDeSoftware
---


## 📚 Idea/Concepto 
El acoplamiento en desarrollo de software es la medida de interdependencia entre módulos o clases y refleja cuánto conocen o dependen unos de otros. Un bajo acoplamiento se alcanza mediante la separación entre interfaz e implementación, el uso de inyección de dependencias y la aplicación prudente de la Ley de Demeter, que sugiere interactuar solo con los “amigos inmediatos”. La inyección de dependencias, además, impulsa el principio “Tell, Don’t Ask”, delegando la acción al módulo que posee la información relevante (Information Expert). Existen distintos tipos de acoplamiento —de contenido, común, de control o de datos— cuya severidad define la fragilidad del sistema. Si el acoplamiento es alto, surgen code smells como Feature Envy o Shotgun Surgery, que amplifican los cambios. Mantener bajo acoplamiento, combinado con alta cohesión, permite construir sistemas más modulares, reutilizables y resistentes al cambio sin incurrir en sobreingeniería.

## 📌 Puntos Claves (Opcional)
- Representa el **grado de dependencia** entre módulos; se busca minimizarlo mediante interfaces, DI y la Ley de Demeter.
- El **bajo acoplamiento**, junto con la alta cohesión, permite sistemas más **modulares, reutilizables y resistentes al cambio**.

## 🔗 Connections
- [[ Ley de Demeter]]
- [[Inversión de Dependencias / DI]]

