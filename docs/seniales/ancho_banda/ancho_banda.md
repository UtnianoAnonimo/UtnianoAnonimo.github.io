# Ancho de banda

El ancho de banda es el rango de frecuencias significativas de la señal que un
medio físico de transmisión debe transmitir. Normalmente el ancho de banda se calcula como la diferencia entre la mayor y menor frecuencia de una señal (periódica o no periódica). $$B = \text{frecuencia superior} - \text{frecuencia inferior}$$

Existen "dos" tipos de ancho de banda:

- **Ancho de banda absoluto [Hz]:**
Es el ancho del espectro de frecuencias completo. **Es infinito** ya que se toman todas las armónicas.

- **Ancho de banda relativo [Hz]:**
Es el ancho del espectro de frecuencias donde se **concentra la mayor parte de la energía** de la señal. Normalmente **es finito** ya que se toman algunas armónicas en función del uso que se le dará a la señal.

    ![ancho_banda_relativo](../../assets/ancho_banda_relativo.png)

?>  En transmisiones reales, usamos **el ancho de banda relativo** y no el absoluto, ya que para que una señal pueda ser transmitida por un canal de comunicación, el espectro de frecuencia de esta tiene que entrar en el canal y, en una señal aperiódica, vimos que, en la teoría, su ancho de banda es infinito (y esto no puede entrar en un canal real). Es por eso que a partir de ahora, cuando hablamos de ancho de banda, nos estaremos referiendo al ancho de banda relativa, ya que es con el que trabajaremos.

