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

<img width="846" height="502" alt="image" src="https://github.com/user-attachments/assets/224d5d77-1b26-4c5f-95cc-739c29f05c1a" />

Ejercicio 6: Usando expresiones.

Enunciado:

Esta función debería devolver true si el número es par, false si es impar.

Coloca un breakpoint en la línea del if.
Inspecciona el valor de num % 2 usando una expresión.
Averigua por qué el resultado siempre es el mismo.
Corrige el error.

- Aquí el fallo viene en que la condicion dentro del if deberia de estar entre parentesis "if ((num % 2) = 0)" cumpliendo asi las reglas matematicas donde primero se cumplen los parentesis.

<img width="328" height="248" alt="image" src="https://github.com/user-attachments/assets/40e2331f-2df2-4333-89ca-bcddc5bf5d79" />

Ejercicio 7: Callback defectuoso.

Enunciado:

El programa debería mostrar los datos recibidos, pero lanza un error al ejecutar.

Coloca un breakpoint en la línea callback(dat);.
Observa qué variables existen en ese punto.
Usa Step Into (F11) para entrar en la función callback y detectar la causa del fallo.

- error sintactico en vez de poner "callback(datos)" esta puesto "callback(dat)".

<img width="453" height="244" alt="image" src="https://github.com/user-attachments/assets/e259d220-a3bd-4090-8bd7-e7917ae8b418" />

Ejercicio 8: Evento click sospechoso (HTML + JS).

Enunciado:

Al hacer clic en el botón debería aparecer un mensaje en consola, pero se produce un error.

Abre la depuración en VS Code con Chrome o Edge.
Coloca un breakpoint donde creas que será útil.
Observa qué variable causa el error.
Corrige el código.

- es un erro de sintaxis, en el codigo esta "console.log(msj)" cuando deberia de ser "console.log(msg)".

<img width="561" height="385" alt="image" src="https://github.com/user-attachments/assets/b8f6a54d-2726-4fed-aa32-67f717ab9f53" />

Ejercicio 9: Cálculo misterioso.

Enunciado:

La función debería calcular correctamente el precio final aplicando el descuento, pero los resultados son incoherentes. El segundo log, al descontar el 60% debería devolver 40, no? Sin embargo devuelve 0.

Usa breakpoints para seguir el flujo de ejecución paso a paso.
Observa los valores intermedios de precioFinal y descuento.
Este ejercicio no tiene un error de código, en el sentido estricto. Es un "error humano", por así decirlo.
Encuentra la causa del error y propón una corrección que funcione para los dos caasos de los logs.

El error esta en los datos que se ponen en el segundo console.log. el segundo dato no debería de ser 60 si no 0,6 al ser el descuento, o si era el 60 tendría de ser el 60%, para que se pudiera aplicar el descuento sin llegar a saltar el error o en este caso que los numero den negativo


<img width="862" height="401" alt="image" src="https://github.com/user-attachments/assets/2f56fd5c-4e0f-4a96-aec0-a23ef6331745" />







