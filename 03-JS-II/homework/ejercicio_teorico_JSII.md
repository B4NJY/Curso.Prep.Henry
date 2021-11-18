 * for : Es un ciclo o bucle que contiene 2 expreciones 1 condicion y la sentencia
 Ejemplo : for (1° expresion ; Condicion ; 2° Expresion){
            Sentencia
 }

 for (let i = 0 ; i < 10 ; i++){
     console.log(i);
 }

 El ciclo aqui , declara una variable i con el valor de 0 que utilizaremos como contador (1° expresion). 
 Luego si la variable i es mayor 10 se ejecurata el codigo (Condicion).
 Y por ultimo le incrementamos 1 a la variable i (2° expresion).
 Luego se ejecuta el codigo . En este caso imrpimira en pantalla el valor de i.

 Ahora el ciclo comienza de nuevo pero el valor de i se incremento a 1 , mientras la condicion se cumpla se ejecutara el codigo hasta que deje de cumplirse.

OPERADORES LOGICOS

 * && : Operador "AND" . evalua si ambas expresiones son true. en caso de que lo sean devolvera true. si al menos una no lo es devolvera false

Ejemplo : 
let y = 10 < 20 && 5 < 10 ;
console.log(y)

Aqui imprimira en pantalla true , ya que 10 es menor que 20 YYY 5 es menor que 10.

 * || : Operador "OR". evalua si al menos 1 de las expresiones es true, en caso de que al menos 1 de las expresiones sea true , devolvera true.

Ejemplo:
let y = 10 < 2 || 5 < 10 ;
console.log(y)

Aqui imprimira en pantalla true. Aunque la primer condicion es falsa ya que 10 No es menor que 2 , pero si se cumple la segunda expresion ya que 5 es menor que 10.
y el operador "||" al hayar al menos un true , aquie se imprimira en pantalla true.

 * '!' : el operador "NOT devuelve el valor opuesto que se le pasa.

 Ejemplo:

 let y = !(10 < 2 || 5 < 10) ;
console.log(y)

Es la misma expresion que la anterior , solo que aqui el programa imprimira en pantalla false , ya que da lo contrario del valor de la expresion que como ya vimos es true.
