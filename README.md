# modos-sincrono-y-asincrono
aqui les hablaremos sobre el modo de envio ya rea multicast y unicast por emisor y receptor o sea simultaneo
*********************
Comunicación Sincrónica: es una técnica que consiste en el envío de una trama de datos (conjunto de caracteres) que configura un bloque de información comenzando con un conjunto de bits de sincronismo (SYN) y terminando con otro conjunto de bits de final de bloque (ETB). En este caso, los bits de sincronismo tienen la función de sincronizar los relojes existentes tanto en el emisor como en el receptor, de tal forma que estos controlan la duración de cada bit y carácter.
Características
Los bloques a ser transmitidos tienen un tamaño que oscila entre 128 y 1,024 bytes. La señal de sincronismo en el extremo fuente, puede ser generada por el equipo terminal de datos o por el módem. Cuando se transmiten bloques de 1,024 bytes y se usan no más de 10 bytes de cabecera y terminación, el rendimiento de transmisión supera el 99 por 100.

Ventajas
Posee un alto rendimiento en la transmisión
Los equipamientos son de tecnología más completa y de costos más altos
Son aptos para transmisiones de altas velocidades (iguales o mayores a 1,200 baudios de velocidad de modulación)
El flujo de datos es más regular.

Comunicación Asincrona: En esta transmisión el emisor decide cuando va a enviar el mensaje por la red, mientras que el receptor no sabe en que momento le puede llegar dicho mensaje, para esto se utiliza un bit de cabecera que va al inicio de cada carácter y uno o dos bits de parada que van al final de ese mismo carácter, esto se hace con la finalidad que tanto el emisor como el receptor puedan sincronizar sus relojes y poder decodificar el mensaje.
En este tipo de transmisión no se maneja mucha velocidad ya que cada carácter es transmitido de uno en uno y por lo tanto puede ser un poco lenta.
