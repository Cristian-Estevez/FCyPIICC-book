# Modelado de amenazas

## CIA $ STRIDE:

#### _`CIA:`_

Una técnica rápida para analizar una arquitectura es utilizar la tríada de seguridad (`Confidencialidad`, `Integridad`, `Disponibilidad`), de esta manera se observa cada uno de los componentes de la arquitectura, la necesidad de negocio, el funcionamiento del sistema y la topología; y evaluar si se aseguran cada uno de los principios de la tríada.

#### _`STRIDE:`_

Es un modelado de amenazas desarrollado para la identificación de amenazas. Es utilizado en desarrollo de software y consiste en descomponer una arquitectura en componentes, y analizar cada uno de estos contra el conjunto de amenazas STRIDE.

| Amenaza                   | Propiedad deseada |
| ------------------------- | ----------------- |
| `S`poofing                | Autenticidad      |
| `T`apering                | Integridad        |
| `R`epudy                  | No repudio        |
| `I`nformation disclosure  | Confidencialidad  |
| `D`enial of service       | Disponibilidad    |
| `E`levation of privileges | Autorización      |

\*Lectura sugerida: "A STRIDE-based Security Architechture for Software-Defined Networking - Fabian Ruffy."
