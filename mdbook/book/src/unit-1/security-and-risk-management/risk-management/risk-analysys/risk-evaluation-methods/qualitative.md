# Método cualitativo

Este método está orientado a aspectos soft se una organización o a valores intangibles (imgen, mercado, etc), si bien posee un alto nivel de subjetividad (por estar basado en el juicio, experiencia e intuición), permite establecer indicaciones generales de áreas de riesgo significativo.

### Probabilidad de ocurrencia:

| Nivel de probabilidad | Definición                                                                                                                                                                                                                                                       |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `ALTO`                | La _fuente_ de `amenaza` (_agente_) posee alta _motivación_ y suficiente _capacidad_, o el incidente ha **ocurrido frecuentemente** en el pasado; y los `controles` para prevenir que la `vulnerabilidad` sea explotada no son efectivos.                        |
| `MEDIO`               | La _fuente_ de `amenaza` (_agente_) posee _motivación_ y _capacidad_, o el incidente ha ocurrido en **ciertas ocaciones** en el pasado; pero los `controles` existentes serían capacez de prevenir que la `vulnerabilidad` sea explotada.                        |
| `BAJO`                | La _fuente_ de `amenaza` (_agente_) carece _motivación_ o _capacidad_, o el incidente **no ha ocurrido** en el pasado o los `controles` se encuentrane en condiciones de prevenir, o al menos impedir significativamente, que la `vulnerabilidad` sea explotada. |

### Análisis de impácto:

| Nivel de impacto | Definición                                                                                                                                                                                                                                                                                                                          |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `ALTO`           | **La ocurrencia del incidente provoca:** `1.` Una pérdida económica superior a $...., o `2.` La pérdida, divulgación o modificación no autorizada de información de alta criticidad, o `3.` Un daño considerable a las actividades, o `4.` Un daño considerable a la imagen o reputación, o `5.` Perjuicios graves a seres humanos. |
| `MEDIO`          | **La ocurrencia del incidente provoca:** `1.` Una pérdida económica superior a $...., o `2.` La pérdida, divulgación o modificación no autorizada de información de criticidad media, o `3.` Un daño a las actividades, o `4.` Un daño a la imagen o reputación, o `5.` Perjuicios a seres humanos.                                 |
| `BAJO`           | **La ocurrencia del incidente provoca:** `1.` Una pérdida económica superior a $...., o `2.` La pérdida, divulgación o modificación no autorizada de información de criticidad baja, o `3.` Un daño no significativo a las actividades, o `4.` Un no significativo a la imagen o reputación.                                        |

### Determinación del riesgo:

| Probabilidad de ocurrencia | Impacto BAJO (10)       | Impacto MEDIO (50)      | Impacto ALTO (100)       |
| -------------------------- | ----------------------- | ----------------------- | ------------------------ |
| `ALTO` (1,0)               | MEDIO **10 x 1.0 = 10** | ALTO **50 x 1.0 = 50**  | ALTO **100 x 1.0 = 100** |
| `MEDIO` (0,5)              | BAJO **10 x 0.5 = 5**   | MEDIO **50 x 0.5 = 25** | ALTO **100 x 0.5 = 50**  |
| `BAJO` (0.1)               | BAJO **10 x 0.1 = 1**   | BAJO **50 x 0.1 = 5**   | MEDIO **100 x 0.1 = 10** |

\* escala aplicada: `ALTO` = 50 - 100; `MEDIO` = 10 - 49; `BAJO` = 1 - 9.
