# Identificación, Autenticación, Autorización

### Identificación:

- Es el acto de proveer credenciales que permitan identificar la _`IDENTIDAD`_ de un sujeto.

### Autenticación:

- Es el acto de _comprobación de las credenciales_ recibidas con el objetivo de _`DETERMINAR`_ si el sujeto es quien dice ser.

### Autorización:

- Es el acto de deteminar los _`permisos de acceso`_ de un sujeto identificado y autenticado sobre un objeto.

---

### Técnicas de identificación y autenticación:

1. Tipo 1: Algo que conoces
1. Tipo 2: Algo que tienes
1. Tipo 3: Algo que eres (físicamente)

\* Autenticación de 2 factores (**2FA**) refiere a la utilización de dos `tipos` de factor identificadores para la realización de la autenticación.

---

### Algo que conoces (tipo 1):

- Caso ideal: "One time password"
- Contraseña estática: aquella que se mantiene durante cada sesión de logon.
- Contraseña dinámica: aquella que cambia cada vez que el usuario se identifica
- Passphrase: secuencia de caracteres, usualmente de mayor longitud de la permitida para una contraseña. Esta passphrase se utiliza para determinar una contraseña virtual.

### Algo que tienes (tipo 2):

- Tokens
- Smart cards
- Llaves
- etc...

### Algo que eres (tipo 3):

- Sistemas biométricos:
  Método automatizado de identificación o autenticación de un sujeto vivo basado en espectos físiológicos o de comportamiento
  - Tipos:
    - Huellas dactilares
    - Retina
    - Iris
    - Cara
    - Geometría de la mano
    - Voz
    - Dinámica de la firma a mano alzada
  - Ventajas:
    - No pueden ser prestados como una llave o token
    - No se pueden olvidar
    - Buena relación entre usabilidad, costo y presición
    - Poco esfuerzo para autenticar e identificar al usuario
    - Alta fiabilidad para identificar a los usuarios correctamente sin errores
    - Duran para "siempre"...
  - Desventajas:
    - Adquisición
    - Rechazo
  - Privacidad:
    - Seguimiento y vigilancia:
      Permiten seguir y vigilar los movimientos de una persona a lo largo del día.
    - Anonimicidad:
      Si la identificación esta asociada a una BBDD se pierde mucha anonimicidad.
    - Profiling:
      Recopilación de datos acerca de transacciones realizadas pro un individuo en particular, permite definir un perfil de las preferencias, afiliaciones y creencias del individuo.

---

## Factores:

| Tipo               | Pro                                     | Contra                                                                    |
| ------------------ | --------------------------------------- | ------------------------------------------------------------------------- |
| `Algo que conoces` | `1.` Barato; `2.` Fácil de implementar; | `1.` Fácil de adivinar;`2.` Sniffers y diccionarios; `3.` Usuarios;       |
| `Algo que tienes`  | `1.` Dificil de atacar;                 | `1.` Puede perderse o robarse;`2.` Caro para implementar;                 |
| `Algo que eres`    | `1.` Portable; `2.` Fácil de utilizar;  | `1.` Caro para implementar;`2.` Rechazo del usuario; `3.` Tasas de error; |
