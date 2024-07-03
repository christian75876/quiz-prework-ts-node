JavaScript Básico:

Describe qué es una función en JavaScript y cómo se declara.
R/: Una funcion en js es un fragmento de codigo el cual puede ser utilizado las veces que se requiera, se cuentan con dos tipos de funciones basicas las que son array funtions y las funtions.

const Funtion = () => {};
funtion saludar() = {};


Manipulación del DOM:

Explica cómo seleccionar un elemento del DOM y cambiar su contenido.
R/: const a = Document.querySelector(#id);

Programación Orientada a Objetos (OOP):

¿Qué es una clase en JavaScript y cómo se define una?

R/: Una clase es un elemento el cual tiene propiedades y atirbutos que puede ser heredados por otros elementos creados de su instancia.

class Padre = {};

Eventos en JavaScript:

¿Cómo se agrega un evento de clic a un botón en JavaScript?

R/: document.addEventListener("click", function);

Variables y Tipos de Datos:

Explica las diferencias entre var, let, y const en JavaScript.

R/: LAs diferencias entre var, let, y const en JavaScript son que Var es una variable la cual se declara de forma global en javascript y esta esta deprecada. 
    let es una variable la cual solo es declarada en un entorno del codigo ejemplo dentro de una funcion y fuera de ella serian dos variables distintas estas pueden variar su valor en la ejecucion del algoritmo y poder tener el mismo nombre.
    cosnt son constantes del codigo y son declaradas tambien de forma local en el codigo y no pueden variar en la ejecución del algoritmo

Control de Flujo:

¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?

R/: las estructuras de control son aquellas que me permiten condicionar la ejecución del algoritmo.
    if, else, while, for

Funciones de Flecha:

Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.

R/: Son funciones que se ejecutan cuando son llamadas en el algoritmo y luego se detruyen, se usan similar a las funciones 
    const Funtions = () =>{};

JSON:

¿Qué es JSON y cómo se utiliza en JavaScript?

R/: Un tipo de archivo que se utiliza para almacenar, administrar y condicionar información 

Promesas:

Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.

R/; Una promesa es una funcion la cual va a tener un resultado ya sea pendiente, resuelto ó rechazado.

Depuración:

¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?

R/: PAra depurar podemos usar los motores de los navegadores en la ejecucion de herramientas de administrador

Preguntas de Selección Múltiple (20)

¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
A) var myVariable;
B) variable myVariable;
C) let myVariable;
D) A y C son correctas.
Opcion: D


¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
A) push()
B) pop()
C) shift()
D) unshift()
Opción: A


¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
A) ==
B) ===
C) !=
D) !==
Opción: B


¿Cuál es la salida del siguiente código?
console.log(typeof null);
A) null
B) undefined
C) object
D) number
Opción: B


¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
A) forEach()
B) map()
C) filter()
D) Todas las anteriores
Opción: D


¿Qué se entiende por “hoisting” en JavaScript?
A) Declaraciones de variables y funciones se mueven al principio de su ámbito.
B) Es un término para describir la eliminación de variables.
C) Es un método para agrupar varias funciones.
D) Ninguna de las anteriores.
Opción: A


¿Cuál es la diferencia entre null y undefined en JavaScript?
A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.
C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
D) No hay diferencia.
Opción: A


¿Cuál es el propósito del método Array.prototype.map()?
A) Modificar el array original.
B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.
C) Filtrar los elementos de un array.
D) Encontrar un elemento en un array.
Opción: B


¿Qué es el Event Loop en JavaScript?
A) Un ciclo que controla las llamadas recursivas.
B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
C) Un método para iterar sobre arrays.
D) Ninguna de las anteriores.
Opción: B


¿Cuál es la salida del siguiente código?

console.log(0.1 + 0.2 === 0.3);
A) true
B) false
C) undefined
D) NaN
Opción: B


¿Qué se entiende por strict mode en JavaScript?

A) Un modo que permite utilizar características experimentales.
B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
C) Un método para validar datos.
D) Ninguna de las anteriores.
Opción: D


¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

A) let obj = {};
B) let obj = Object.create();
C) let obj = new Object();
D) A y C son correctas.
Opción: D


¿Qué es un callback en JavaScript?

A) Una función que se pasa como argumento a otra función.
B) Un tipo de variable especial.
C) Un método para declarar funciones.
D) Ninguna de las anteriores.
Opción: A


¿Cuál es el propósito de async y await en JavaScript?

A) Ejecutar funciones síncronas.
B) Manejar operaciones asincrónicas de manera más simple y legible.
C) Declarar variables globales.
D) Ninguna de las anteriores.
Opción: A


¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

A) Arrays
B) Strings
C) Objetos
D) Ninguna de las anteriores.
Opción: A


¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

A) JSON.parse()
B) JSON.stringify()
C) toString()
D) parseInt()
Opción: B

¿Qué es un Promise en JavaScript?

A) Una función que se ejecuta inmediatamente.
B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
C) Un método para declarar variables.
D) Ninguna de las anteriores.
Opción: B


¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

A) push()
B) pop()
C) shift()
D) unshift()
Opción: D


¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente.
C) No hay diferencia entre ellos.
D) Ambos almacenan datos solo durante la sesión del navegador.
Opción: D


¿Qué método se utiliza para detener la propagación de un evento en el DOM?

A) event.stopPropagation()
B) event.preventDefault()
C) event.stop()
D) event.cancel()
Opción: B