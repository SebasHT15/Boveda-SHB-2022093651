---
Fecha de creación: 2025-11-06 17:47
Fecha de Modificación: 2025-11-06 17:47
tags:
  - arquitectura
  - ArquitecturaDeSoftware
  - ArquitecturaYDiseño
Tema: ArquitecturaDeSoftware
---


## 📚 Idea/Concepto 

La arquitectura de software de microkernel es un estilo de diseño monolítico modularizado en el que un núcleo mínimo (core) concentra las funciones esenciales, mientras que la lógica especializada se delega a módulos externos de complemento (plug-ins). Estos plug-ins se registran en un mecanismo de registro (registry), que mantiene información sobre su nombre, contrato de datos y protocolo de acceso. Cada plug-in define un contrato que especifica el comportamiento que ofrece, los datos de entrada y salida, y la forma en que puede ser invocado por el núcleo. Este esquema promueve alta cohesión dentro de los plug-ins y bajo acoplamiento con el core, lo que reduce la complejidad del sistema, mejora la mantenibilidad y permite agregar o reemplazar funcionalidades sin afectar la estabilidad del núcleo. Además, el aislamiento de los componentes volátiles incrementa la confiabilidad y facilita la evolución continua del sistema.
## 📌 Puntos Claves (Opcional)
- Divide el sistema en un **núcleo mínimo (core)** y **módulos de complemento (plug-ins)** registrados dinámicamente.
- Promueve la **alta cohesión y bajo acoplamiento**, aislando código volátil y facilitando la extensibilidad sin alterar el núcleo.

## 🔗 Connections
- [[ Plug-in Architecture]]
- [[Plug-in Architecture]]
