1.Funciones Callback: Es una funcion que es pasada como argumento a otra funcion para que sea "llamada de nuevo"(call back)en un momento posterior.La combinacion de estas 2 funciones es lo que nos permite apliar nuestra funcionalidad.

    //Creamos una funcion donde pasaremos como parametro un string y una funcion.
    //La funcion "frase" contiene una variable "fraacion1" y tambien llamara a la funcion
    //que le pasemos (callback).

    function frase(cita,callback){
        let fraccion1 = "Mejor pajaro en mano, " + cita;
        callback(fraccion1);
    };

    //Creamos la funcion que pasaremos como parametro para la funcion anterior, la cual 
    //mostrara en consala los que le pasemos como parametro a esta funcion.

    function logCita(cita){
        console.log(cita);
    };

    //Finalmente llamamos a la funcion "frase", y lesaremos como argumento una porcion de 
    //la frase, y como segundo argumento , le pasaremos la funcion que habiamos creado con 
    //el nombre de "logCita"

    frase("que 100 volando",logCita)
    
    
    
    
    