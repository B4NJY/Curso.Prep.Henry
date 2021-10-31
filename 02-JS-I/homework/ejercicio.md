Ejercicios (Seccion 02-JS-1)

* Variables: Es un espacio reservado en la memoria para almacenar un dato.
* String: Es una cadena de caracteres.  De esta manera los datos de tipo "String" sirven para definir palabras.
* Funciones (argumentos , `return`) : Una funcion es un bloque de codigo que realiza una funcion especifica. 
A una funcion se le pasan ciertos argumentos , ciertos valores los cuales va aprocesar la funcion (Esto es opcional). 
return : la funcion va a retornar los nuevos valores. Que van a ser los resultadors de los procesos que realizo la funcion .

EJEMPLO: 

(La funcion "saludar" pide un argumento o parametro , que lo llamaremos "nombre". La funcion que va a realizar cuando se la llame es imprimir
un mensaje "Hola (nombre) , Bienvenido a Henry , donde el nombre se lo pasaremos nosotros , ejemplo :

        function (saludar){
                console.log("Hola " + nombre  + " , Bienvenido a Henry");
        }                                                     

        saludar("Benjamin");
        saludar("Maria");
        saludar("Pepe");

*Declaracion if : Es una condicion , si esta se cumple , el bloque de codigo dentro de esta , se ejecutara. EJEMPLO:
Hemos declarado una variable llamada "x" con el valor de 20. 
la condicion (if) dice que si la variable "x" es mayor que 50 , se ejecutara el codigo , e imprimira en la pantalla "Es mayor que 50"
Si no se cumple esa condicion, no se ejecutara el codigo, dentro del bloque de codigo.

        let x = 20
                if (x > 50){
                        console.log("Es mayor que 50")
                }

*Valores Booleanos (true, false): Es un dato que puede tener 2 valores : true(verdadero) o false(falso) EJEMPLO: Declaramos 2 variables "z" e "i". El codigo imprimira en consola "false" , ya que los datos de las variables no son iguales.

                let z = 2;
                let i = 4;
                console.log(z==i);