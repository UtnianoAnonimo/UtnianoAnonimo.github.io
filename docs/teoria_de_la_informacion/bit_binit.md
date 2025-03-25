# Bit y Binit

Hay que recalcar que muchas veces se los puede confundir, ya que pueden valer lo mismo, pero un bit y un binit no son lo mismo.

Un bit es la unidad más pequeña de medida de información y un binit es un dígito binario [0;1] (puede ser denominado como simbolo también).

Para contextualizar: Supongamos que se genera un mensaje que tiene una probabilidad $P_a = \frac{2}{3}$ de generarse y un mensaje B, pero con una probabilidad de $P_b = \frac{1}{3}$. Usando la **[fórmula de información]()** tenemos que:
$$ I_a = \log _2 \frac{1}{P_a} = \log _2 \frac{3}{2} = 0.58 [bits] $$
$$ I_b = \log _2 \frac{1}{P_b} = \log _2 3 = 1.58 [bits] $$

Como podemos ver, para el mensaje A, estaríamos serializando 1 símbolo (binit) pero en contraparte, la información que generamos no es de 1 bit como podriamos suponer a simple vista, sino que es de 0.58 bits. ¿Y esto por qué se da? Porque las probabilidades de los distintos mensajes (en este caso A y B) no son **equiprobables**. En caso de serlo, la probabilidad de cada uno sería:
$$ P(mensaje) = \frac{1}{2} = 0.5 $$ por lo que:
$$ I_x = \log _2 \frac{1}{P_x} = \log _2 2 = 1 [bit] $$

