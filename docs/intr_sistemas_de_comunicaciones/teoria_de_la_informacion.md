# Teoría de la Información

La teoría de la información es una rama de la teoría de la probabilidad que se ocupa de la medición de la información, cómo representar la información y también la capacidad de los sistemas de comunicación de transmitir y procesar información.

Tiene como objetivo estudiar las señales y el contenido de información que poseen.

![teoria_de_la_informacion_diagrama](../assets/teoria_de_la_informacion_diagrama.png)

## Medida de Información (1er Principio)

**Cuanto menos probable sea la aparición de un fenómeno, más información tiene.**

Un mensaje de poca probabilidad contiene mucha información para el receptor. No es lo mismo recibir el mensaje "en verano hará calor" que "en verano hará frio" ya que uno es muy probable, casi asumible, y el otro causará que el receptor cambie.

Por lo tanto, la información es inversamente proporcional a la probabilidad: $$I = \frac{1}{P_a}$$

## Información Mutua (2do Principio)

## Bit y Binit

Hay que recalcar que muchas veces se los puede confundir, ya que pueden valer lo mismo, pero un bit y un binit no son lo mismo.

Un bit es la unidad más pequeña de medida de información y un binit es un dígito binario [0;1] (puede ser denominado como simbolo también).

Para contextualizar: Supongamos que se genera un mensaje que tiene una probabilidad $P_a = \frac{2}{3}$ de generarse y un mensaje B, pero con una probabilidad de $P_b = \frac{1}{3}$. Usando la **[fórmula de información]()** tenemos que:
$$ I_a = \log _2 \frac{1}{P_a} = \log _2 \frac{3}{2} = 0.58 [bits] $$
$$ I_b = \log _2 \frac{1}{P_b} = \log _2 3 = 1.58 [bits] $$

Como podemos ver, para el mensaje A, estaríamos serializando 1 símbolo (binit) pero en contraparte, la información que generamos no es de 1 bit como podriamos suponer a simple vista, sino que es de 0.58 bits. ¿Y esto por qué se da? Porque las probabilidades de los distintos mensajes (en este caso A y B) no son **equiprobables**. En caso de serlo, la probabilidad de cada uno sería:
$$ P(mensaje) = \frac{1}{2} = 0.5 $$ por lo que:
$$ I_x = \log _2 \frac{1}{P_x} = \log _2 2 = 1 [bit] $$

## Entropia

