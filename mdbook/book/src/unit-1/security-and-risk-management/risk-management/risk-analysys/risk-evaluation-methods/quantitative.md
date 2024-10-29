# Método cuantitativo

Este método permite realizar una evaluación y resultados basados en métricas, cuantificar los parámetros de la tríada (CIA) en `términos monetarios`. Permite un análisis `costo-beneficio` de los controles a aplicar y principalmente un seguimiento y evaluación de la gestión de riesgo.

| Nombre                                    | Definición                                                                                                                      | Fórmula                              |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ |
| `Factor de exposición (EF)`               | El `EF` es el `porcentaje` de pérdida sobre el valor de un activo en caso de concretarse una amenaza                            | 0% ≤ **EF** ≤ 100%                   |
| `Expectativa de pérdida individual (SLE)` | El `SLE` es el `valor monetario` asociado a un evento determinado. Representa la pérdida producida por una `amenaza` individual | **SLE** = Valor del activo \* **EF** |
| `Tasa de ocurrencia anual (ARO)`          | El `ARO` representa la `frecuencia` estimada de ocurrencia de un evento en el perídodo de _un año_                              | 0 ≤ **ARO** ≤ ∞                      |
| `Expectativa de pérdida anualizada (ALE)` | El `ALE` es el **pérdida** anual producida por una `amenaza individual`                                                         | **ALE** = **SLE** \* **ARO**         |

---

### Ejemplo:

**Activo**: Base de datos

**Valor**: $100.000

**Amenaza**: Malware

**EF**: estimado en un _25%_

**ARO**: 2 veces al año

**SLE**: $100.000 (_Valor del activo_) \* 0.25 (_EF_) = $25.000

**ALE**: $25.000 (_SLE_) \* 2 (_ARO_) = $50.000
