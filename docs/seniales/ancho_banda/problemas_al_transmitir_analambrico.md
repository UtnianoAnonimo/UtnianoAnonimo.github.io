# Problema a la Hora de Transmitir Datos por una Línea de Transmisión Alámbrica

Las señales que nos interesan en las comunicaciones son las **no periódicas**, ya que son **con las que transmitimos datos**. Estas señales, como ya vimos, poseen normalmente un ancho de banda infinito.

También sabemos que los medios físicos de transmisión tienen un ancho de banda máximo, es decir, permiten pasar hasta ciertas frecuencias. Como vimos, a medida que la frecuencia una señal aumenta, sucede el **[efecto skin](../../fisica_de_las_comunicaciones/efecto_skin)** y si continúa aumentando el conductor se transforma en una antena y las cargas comienzan a ser irradiadas.

Entonces, cuando nosotros transmitimos datos por una línea de transmisión alámbrica como puede ser un cable UTP, estos se comportan como un **[filtro pasa bajo]()**. Supongamos que tenemos una señal de pulsos cuadrados, vemos que la señal se deforma al transmitirla.

![ej_filtro_utp](../../assets/ej_filtro_utp.png)


Esto es debido a que el cable actúa como un **[filtro pasa bajo]()** y recorta todo el rango de altas frecuencias que al fin y al cabo contiene parte de la energía de la señal y esto causa que los pulsos se modifiquen.

![ej_filtro_problema](../../assets/ej_filtro_problema.png)

Para que la señal sea exactamente igual, el ancho de banda tendría que ser infinito y esto no es posible.