# Basados en Filtrado de paquetes

`(IP Filters, packet filter)`

- Capa 3 (Internet protocol) - Permite o deniega el paso de datagramas según un conjunto de reglas.
- Solo entienden d direcciones IP.
- Comparan los encabezados IP, TCP y UDP para compararlos contra las ACL (Access controls list) configuradas

#### _Ventajas_:

- Velocidad.
- Su característica de filtrado se encuentra en otros dispositivos.

#### _Desventajas_:

- Limitados en capacidades.
- No detectan paquetes a nivel de aplicación.
- Configuración.
