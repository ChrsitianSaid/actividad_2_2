LOG A :

¿Qué imprimirá la consola? : Se imprimirá por consola undefined

Justificación Teórica: Ya que la variable tiene hoisting, es decir, se llama a producto antes de que tenga su valor asignado, por eso es undefined.

LOG B : 

¿Qué imprimirá la consola? : Se va a imprimir "Teclado Mecanico"

Justificación Teórica: Lo imprimirá correctamente al encontrarse ya con la variable producto creada. 

LOG C : 

¿Qué imprimirá la consola? : Imprimirá "25"

Justificación Teórica: Lo imprimirá porque sustituye el descuento 10 por un 25, ya que let tiene un ámbito de bloque.

LOG D : 

¿Qué imprimirá la consola? : Imprimirá "10"

Justificación Teórica: Lo imprimirá debido a que el descuento = 25 es un let y tiene un ámbito de bloque

LOG E :

¿Qué imprimirá la consola? : Imprimirá Log E ¡ERROR CATÁSTROFICO

Justificación Teórica: Lo imprimirá así debido al mismo problema de arriba, que como el impuesto es una const tiene ámbito de bloque y no se aplica. 

LOG F :

¿Qué imprimirá la consola? :Imprimirá Log F ¡ERROR CATÁSTROFICO!

Justificación Teórica: Ya que el precio también tiene ámbito de bloque y porque se encuentra en el TDZ al ser un let y llamarse antes de crearla; si fuese un var sería undefined. 
