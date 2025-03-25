# Sincronismo

Cuando un emisor transmite cierta información es necesario que el receptor pueda recuperar todos los símbolos que son enviados por el emisor a través del canal de comunicaciones. El cabezal del receptor tiene que **ser capaz de censar todos los símbolos** que vienen uno detrás de otro.

Entre cada símbolo hay un tiempo denominado tiempo del bit y se espera que este tiempo sea constante de forma que el cabezal del receptor pueda ajustar su puntero de lectura a esta velocidad de aparición de los símbolos.

El emisor, sin embargo, va a emitir el conjunto de símbolos a una frecuencia de reloj propia que puede no ser igual a la del receptor ¿cómo podemos hacer para que las frecuencias de reloj de emisor y receptor se sincronicen?