


1.Objetos: Es una unidad de un programa , que tiene propiedades , caracteristicas (que se las define como clave:valor o  key:value) y metodos, que contienes funciones , que le dan funcionalidad al objeto.

2.Propiedades: Es una asociacion entre un nombre y un valor.

    Ejemplo:
    
    let fruta = {
        nombre: 'frutilla',
        color: 'rojo',
        cantidad: 3
    }

Creamos el objeto con el nombre "fruta" , y las propiedades de ese objeto son 'nombre' , 'color' y 'cantidad'. Cada una de esas propiedades tiene asignado un valor :

    //(clave)   (valor)
      nombre  : 'frutilla',
      color   : 'rojo',
      cantidad:   3

3.Metodos: Dentro de los objetos ,los valores se pueden establecer como funciones. Cuando guardamos una funcion dentro de una propiedad del objeto , a esta se la denomina como METODO.
La "clave" seria el nombre del metodo, y el "valor" seria la funcion. Ejemplo

    //Tenemos el objeto "fruta

    let fruta = {
        nombre: 'frutilla',
        color: 'rojo',
        cantidad: 3

    //Le asignamos una propiedad que sera un  metodo que se llama "Saludar" , el cual contiene un valor que es una funcion, que hara que el objeto imprima en pantalla un mensaje.

        saludar : function(){
            console.log('Hola ,soy una frutilla!')
        }

    }

4.Bucle 'for...in' : Sirve para iterar sobre cada clave-valor del obejto. Asi como con un bucle for , lo utilizamos para recorrer una matriz o array, con el bucle 'for...in' recorremos un objeto. Ejemplo:

    //Creamos el objeto usuario =

    let usuario = {
        nombre: "Marcelo",
        edad: 24,
        hobbies: "tenis"
    }

    //Creamos el bucle for...in. donde creamos una variable, el bucle recorrera el objeto que le indicamos ,y va a almacenar las clave:valor(propiedades) de ese objeto.

    for(let datos in usuario){
        console.log(datos);
        console.log(usuario[datos])
    }

    //el bucle en este caso , primero mostrara en consola , las claves del objeto usuario, y por segundo, mostrara en pantalla los valores de esas claves.

5.Notacion de puntos VS notacion de corchetes: La notacion de puntos es mas rapida de escribir y mas clara de leer.

La notacion de corchetes permite el acceso a propiedades que contienen caracteres especiales y la seleccion de propiedades mediante variables.

