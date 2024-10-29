# Consideraciones del diseño de red

#### _`Isolado, separación y compartimentalización:`_

Con el isolado o aislamiento, la separación y compartimentalización, se busca asegurar que ante un incidente (falla, compromiso) en una parte del sistema, este quede reducido solo a esa porción de la red. Evitando fallas en otras partes o una progresión del compromiso.

### _`Políticas:`_

La aplicación de políticas brinda la capacidad de aplicar el comportamiento permitido entre los sistemas conectados, las aplicaciones, los usuarios, las redes y subredes. El ejemplo más claro es el establecimiento de ACL (Access control lists).

### _`Identidad y confianza:`_

Cuando nos referimos a identidad, nos referimos a la capacidad de un sistema para identificar a las entidades que acceden a un recurso. Se configura también un nivel de confianza otorgado a cada entidad según la necesidad (mínimo privilegio).

### _`Instrumentación y monitoreo:`_

Se refiere a la capacidad de supervisar el comportamiento y uso de la red (sus recursos, sistemas, usuarios, tráfico), desarrollando la capacidad de detectar cualquier evento de seguridad.

### _`Correlación:`_

Es la capacidad de vincular los eventos detectados en la red. Permite interpretar, analizar y clasificar la información obtenida del monitoreo. Por medio de ella se pueden contextualizar los eventos, determinar un escenario o situación dada. Cuanto mejor sea la **`calidad`** del monitoreo (_no cantidad_), mejor será la capacidad de acción.

### _`Resiliencia:`_

Es la capacidad de recuperación posterior a un incidente. Indica la madurez de una arquitectura para volver a un estado de operatividad ante situaciones anómalas, no controladas o inseperadas. Ej: redundancia, disponibilidad, capacidad operativa, planes de contigencia, respuesta a incidentes, etc
