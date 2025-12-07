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
Una Public IP en el cloud es una dirección accesible globalmente que permite que recursos desplegados dentro de una red virtual privada (como máquinas virtuales, balanceadores o gateways) se comuniquen con Internet. Su uso implica normalmente un mecanismo de Network Address Translation (NAT), que traduce el espacio privado de la VPC hacia direcciones públicas para habilitar tráfico entrante y saliente. Las IP públicas pueden ser dinámicas —asignadas temporalmente— o estáticas, conservadas de forma permanente para servicios que requieren direcciones fijas. Desde una perspectiva de ingeniería, su exposición demanda controles estrictos mediante Network Security Groups o firewalls para limitar únicamente el acceso necesario. Además, su uso tiene impacto en costos operativos, ya que el tráfico de salida (egress) asociado a conexiones a través de la IP pública se factura según consumo.

## 📌 Puntos Claves (Opcional)
- Dirección accesible globalmente para exponer servicios.
    
- Opera mediante NAT para conectar redes privadas.
    
- Puede ser estática o dinámica.
    
- Requiere configuración de seguridad (NSGs/firewalls).
    
- Egress traffic asociado impacta costos.