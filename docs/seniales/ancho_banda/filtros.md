# Filtros

Los filtros nos permiten delimitar que frecuencias (o ancho de banda) nos interesa transmitir o recibir.

Para estos, se suele usar un concepto llamado **Frecuencia de Corte**. Es un valor de referencia que se toma para determinar, cuando hay una caída/subida de la potencia de una señal. Este cambio no suele ser instantaneo, sino que progresivo.

> [!TIP]
> El valor que se toma de referencia para la Frecuencia de Corte es de 70.7% (ya sea, caida o subida) de su valor máximo, esto ocurre cuando la reactancia capacitiva iguala a la resistencia.

## Filtro Pasa Bajo

Son aquellos que dejan pasar señales de baja frecuencia a partir de la frecuencia de corte.

![filtro_pasa_baja](../../assets/filtro_pasa_baja.png)

## Filtro Pasa Alto

Son aquellos que dejan pasar señales de alta frecuencia a partir de la frecuencia de corte.

![filtro_pasa_alto](../../assets/filtro_pasa_alto.png)

## Filtro Pasa Banda

Son aquellos que dejan pasar señales de frecuencia comprendidas dentro de dos frecuencias límites $AB = FH - FL$. Es una unión entre un filtro pasa bajo y un filtro pasa alto.

![filtro_pasa_banda](../../assets/filtro_pasa_banda.png)