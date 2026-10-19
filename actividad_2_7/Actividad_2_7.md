Ejercicio 1: Variable inexistente:

Enunciado:

-Este script debería mostrar la suma de a y b, pero algo no funciona.

-Usa un breakpoint en la línea del console.log.
-Inspecciona las variables activas y averigua qué causa el error.
-Corrige el código para que muestre correctamente el resultado.

-En este ejeercisio realmente no hace falta usar un breakpoint, y las variables estan bien, en este caso el error es un error sintactico ya que el metodo "result" al llamarlo en el console.log se le llama como "reslt" y este no existe. 

<img width="346" height="90" alt="image" src="https://github.com/user-attachments/assets/ef34365d-3794-4b49-98e8-fc7fa25e7a6d" />

-Para solucionarlo habria que cambiar en console.log la llamada del metodo "reslt" a "result".

<img width="412" height="103" alt="image" src="https://github.com/user-attachments/assets/5ae795ea-33de-4a16-8f85-3c38191e5b44" />


<br> Ejercicio 2: Comparaciones sospechosas.

Enunciado:

-El programa debe indicar si alguien es mayor o menor de edad.

-Coloca un breakpoint en la línea del if.
-Comprueba el valor de la condición y determina por qué siempre se ejecuta la misma rama aunque cambies el valor de edad.
-Corrige el error lógico.

-El error esta en el if: que esta puesto edad=<18 cuando deberia de ser edad>=18

<img width="394" height="190" alt="image" src="https://github.com/user-attachments/assets/49473336-6d7f-433b-b9f5-d3bab568afa6" />

Ejercicio 3: Return of the Jedi.

Enunciado:

Esta función debería devolver el resultado de una multiplicación, pero no lo hace.

Coloca un breakpoint dentro de la función multiplicar.
Usa Step Into (F11) para entrar en la función.
Observa qué ocurre con la variable resultado y con la llamada desde console.log.
Corrige el código para que funcione como se espera.

- en este caso a la funcion de hace falta el metodo return, el cual si esta en el codigo pero aparece comentado.

<img width="372" height="226" alt="image" src="https://github.com/user-attachments/assets/e003179f-6172-4e71-a0fe-b36341b6eaf0" />

Ejercicio 4: Names, names...

Enunciado:

El objetivo es mostrar un saludo personalizado, pero se produce un error al ejecutar el programa.

Añade un breakpoint en la línea del console.log.
Comprueba qué variables están disponibles en ese momento.
Identifica la causa del error y corrige el código.

- En este ejercicio la variable name no existe, en mi caso lo corregi declarando la variable name y dandole el valor de nombre.

<img width="865" height="200" alt="image" src="https://github.com/user-attachments/assets/78f7b832-03cf-4aeb-a1bc-228c9aded966" />

Ejercicio 5: Out of control

Enunciado:

Este código intenta sumar todos los elementos de un array, pero algo sale mal.

Coloca un breakpoint en la línea dentro del bucle.
Usa Step Over (F10) para recorrer cada iteración.
Observa los valores de i y suma.
Identifica el error y corrígelo.

-en el ejercicio 5 el error es un <= dentro del bucle for, cuando deberia de ser <.

