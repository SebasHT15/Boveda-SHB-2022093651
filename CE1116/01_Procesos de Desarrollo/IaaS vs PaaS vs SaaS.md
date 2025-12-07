---
Fecha de creación: 2025-12-06 22:42
Fecha de Modificación: 2025-12-06 22:42
tags:
  - arquitectura
  - ArquitecturaDeSoftware
  - ArquitecturaYDiseño
Tema: ArquitecturaDeSoftware
---


## 📚 Idea/Concepto 

IaaS (Infrastructure as a Service) proporciona recursos fundamentales como cómputo, redes y almacenamiento bajo un modelo de responsabilidad compartida donde el proveedor gestiona la infraestructura física, pero el usuario controla el sistema operativo, la configuración y las aplicaciones. PaaS (Platform as a Service) ofrece un entorno completo de ejecución —runtimes, bases de datos, CI/CD, orquestadores— reduciendo el control del usuario sobre el sistema operativo a cambio de mayor productividad, aunque puede generar dependencia del proveedor (vendor lock-in). SaaS (Software as a Service) entrega aplicaciones listas para usar donde el proveedor administra todo el stack tecnológico. En ingeniería, estos modelos implican trade-offs claros: IaaS ofrece mayor control y mayor costo operativo; SaaS reduce costo y responsabilidad; y PaaS introduce modelos de cobro como pago por ejecución en plataformas serverless que optimizan elasticidad y uso real.
## 📌 Puntos Claves (Opcional)
- Clasificación según nivel de abstracción del servicio.
    
- IaaS → control total del SO, redes y VMs; mayor costo operativo.
    
- PaaS → plataforma administrada; mayor productividad pero riesgo de vendor lock-in.
    
- SaaS → aplicación lista para usar; mínimo control técnico.
    
- Importancia del modelo de responsabilidad compartida.
    
- Diferencias en modelo de cobro (IaaS fijo, PaaS/serverless por ejecución).