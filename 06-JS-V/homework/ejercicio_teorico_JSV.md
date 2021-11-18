1.Prototype:Todos los objetos tienen una referencia a otro objeto llamado "prototype".
este prototipo es un objeto. cuando le pedimos a un objeto una propiedad que no tiene, la busca en su prototipo. Un prototipo es otro objeto que se utiliza como una fuente de propiedades alternativas.

    //Creamos un constructor llamado "Person" el cual pedira coo parametros (nombre,apellido,edad,dni)

    function Person(nombre,apellido,edad,dni){
	this.nombre = nombre;
    this.apellido = apellido;
    this.edad = edad;
    this.dni = dni
    }

    //Ahora creamos un objeto "newPersona" usando nuestro constructor "Person", y creamos   
    //sus clave:valor , a traves de los parametros del constructor. 

    let newPersona = new Person("Marcelo","Perez",31,78952115);

    //Ahora accedemos al prototype del constructor person, y creamos un metodo dentro de el 
    //llamado "saludo el cual nos devolvera una funcion , que mostrara en consola un mensaje.

    Person.prototype.saludo = function(){
	console.log(`Hola me llamo ${this.nombre}, mi DNI es ${this.dni}`);
    }

    newPersona.saludo();


2.Constructors (de clases): el metodo constructor sirve para crear un objeto a partir de una clase. Este metodo se utiliza dentro de una clase.Puede haber solo un medoto constructor en una clase. Ejemplo:


    //Creamos una clase llamada "Person", La cual va a contener el metodo "constructor", el 
    //cual va recivir parametros para asignar a las propiedades de ese futuro objeto que 
    //construiremos utilizando esa platilla de la clase Person.

    class Person {
        constructor(nombre,apellido,edad,dni){
        this.nombre = nombre;
        this.apellido = apellido;
        this.edad = edad;
        this.dni = dni;
      }
    }

    //Ahora accedemos al prototype de la clase person, donde vamos a crear un metodo 
    //llamado "saludo" , el cual sera una funcion que mostrara en pantalla un mensaje.

    Person.prototype.saludo = function(){
        console.log(`Hola me llamo ${this.nombre},${this.apellido} , y tengo ${this.edad} años`)
    }

    let newPerson = new Person("julieta","morena",37,84562);

    newPerson.saludo();

