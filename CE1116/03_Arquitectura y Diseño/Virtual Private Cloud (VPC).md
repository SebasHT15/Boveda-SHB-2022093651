---
Fecha de creación: 2025-12-06 22:38
Fecha de Modificación: 2025-12-06 22:38
tags:
  - arquitectura
  - ArquitecturaDeSoftware
  - ArquitecturaYDiseño
Tema: ArquitecturaDeSoftware
---


## 📚 Idea/Concepto 
Una Virtual Private Cloud (VPC) es una red virtual aislada dentro de un proveedor de nube pública que replica el comportamiento de una red física tradicional. Permite definir rangos de direcciones IP privados, crear subredes y controlar el flujo de tráfico mediante tablas de ruteo personalizadas y reglas de firewall como los Network Security Groups, las cuales se aplican a las subredes para reforzar la seguridad y modificar el enrutamiento por defecto. Una VPC también habilita la conectividad híbrida hacia entornos on-premise mediante servicios como VPN Gateway o conexiones dedicadas. Además, una VPC está limitada a una región específica, por lo que arquitecturas multirregionales requieren múltiples VPCs interconectadas.

## 📌 Puntos Claves (Opcional)
- Red virtual aislada dentro de la nube pública.
    
- Control total sobre IPs, subredes, tablas de ruteo y reglas de seguridad (NSG).
    
- Mecanismos de enrutamiento personalizables (UDR).
    
- Conectividad híbrida mediante VPN Gateway o conexiones dedicadas.
    
- Limitada a una sola región; multiregión requiere múltiples VPCs.

