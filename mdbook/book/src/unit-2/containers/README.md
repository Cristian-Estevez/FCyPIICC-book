# Contenedores

Un `Contenedor de software` es un método en el que, sobre el núcleo del sistema operativo se ejecuta una capa de virtualización. Utiliza las system-call y no una emulación completa como por ejemplo en la _paravirtualización_ o _virtualización_ de hardware, estos últimos utilizan hipervisores, mientras que la containerización no.

### Descripción:

- Arquitectura cliente-servidor(docker engine):
  - Servidor (docker-daemon)
  - API Rest
  - Cliente (CLI)
- Imagen:
  - Plantilla (template) que es utilizada para crear contenedores.
- Contenedor:
  - Instancia de imagen que se ejecuta de manera aislada, tiene un ambiente y conunto de procesos propio.
- Registros (Docker registry):
  - Almacenan las imágenes (docker hub)
  - Repositorio de imágenes?
- Red:
  - Genera una red propia que puede vincularse o no con la máquina host y entre los diferentes contenedores.
- Almacenamiento:
  - Puede generarse persistencia de datos con la utilización de volúmenes.

### Buenas prácticas:

- Host:
  - Estructura de almacenamiento.
  - Permisos de usuarios y grupos (quien tiene acceso al daemon de docker)
  - Registros (logs)
- Daemon:
  - Tráfico
  - Registros (logs)
- Contenedor:
  - Aplicaciones como mínimo privilegio.
- Registros (Docker registries) seguros.
- Seguridad de las imágenes.
- Entre otros:
  - Eliminar permisos de setuid y setgid (en dockerfile)
  - Restringir permisos de Linux en contenedores
  - Restringir protocolos
  - Restringir puertos
  - Limitar el uso de recursos
  - Asegurar Docker Socket
    - Implementar el uso de TLS
  - Kernel capabilities, restringir según su uso
  - Restringir SystemCalls (Seccomp)
  - DAC vs MAC (Selinux, AppArmor)
  - User namespace remaping
