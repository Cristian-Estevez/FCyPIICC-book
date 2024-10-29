# Basados en Nivel de circuito

`Circuit level gateway`

- Capa 4 (TCP) - monitorea sesiones TCP/IP. _`¿¿¿(Capa 5??)???`_
- Monitorea el intercambio de paquetes para validar una sesión.
- No filtra paquetes individuales sino sesiones.
- La detección se realiza antes de que se establezca la connección.

#### _Ventajas_:

- La información parece venir desde el firewall (Cobertra de red interna).

#### _Desventajas_:

- Al no filtrar paqetes, una vez establecida la conección se puede aprovechar.
- No se puede monitorear el tráfico.
