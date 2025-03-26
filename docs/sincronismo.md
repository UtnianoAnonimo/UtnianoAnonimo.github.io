# Sincronismo

Cuando un emisor transmite cierta información es necesario que el receptor pueda recuperar todos los símbolos que son enviados por el emisor a través del canal de comunicaciones. El cabezal del receptor tiene que **ser capaz de censar todos los símbolos** que vienen uno detrás de otro.

Entre cada símbolo hay un tiempo denominado tiempo del bit y se espera que este tiempo sea constante de forma que el cabezal del receptor pueda ajustar su puntero de lectura a esta velocidad de aparición de los símbolos.

El emisor, sin embargo, va a emitir el conjunto de símbolos a una frecuencia de reloj propia que puede no ser igual a la del receptor ¿cómo podemos hacer para que las frecuencias de reloj de emisor y receptor se sincronicen?

## Niveles de Sincronismo

### Primer Nivel de Sincronismo

El receptor tiene que saber cuándo y por cuanto tiempo tiene que escuchar los bits que recibe.

### Segundo Nivel de Sincronismo

El receptor tiene que saber qué bits agrupar para formar los caracteres. Tengamos en cuenta que el receptor recibirá un conjunto de bits y el tendrá que saber determinar la estructura de los bits (cuáles son información, cuales son bits redundantes, bits de control, entre otros).

La estructuración de los bits la llamaremos formato de trama.

### Tercer Nivel de Sincronismo

Como antes tenía que saber qué bits agrupar para formar caracteres, ahora el receptor tiene que saber que caracteres agrupar para formar un mensaje.
