1. JavaScript Básico:

Describe qué es una función en JavaScript y cómo se declara.

Las funciones en Javascript nos permiten ejecutar algo puede ser una operacion, agregar, quitar, mover, son un trozo de codigo que se le indica que es lo que tiene que hacer y que al llamarlo en otra parte se va a ejecutar.
Existen funciones declaradas y expresadas.

* Las funciones declaradas se definen:

function suma (a,b) {
	return a+b
}

* Las funciones expresadas se definen:

let suma = function (a,b){
	return a+b 
}

2. Manipulación del DOM:

Explica cómo seleccionar un elemento del DOM y cambiar su contenido.

Para seleccionar un elemento del DOM utilizamos: "Document.getElementbyId, Document.getElementbytagname, queryselector.

Y cambiamos su contenido con "Inner.HTML"

3. Programación Orientada a Objetos (OOP):

¿Qué es una clase en JavaScript y cómo se define una?

Una clase es una plantilla que me permite definir caracteristicas (atributos) y comportamientos (metodos) a una entidad (sustantivo)

4. Eventos en JavaScript:

¿Cómo se agrega un evento de clic a un botón en JavaScript?


addEventListener("click", (event) ==> {});

5. Variables y Tipos de Datos:

Explica las diferencias entre var, let, y const en JavaScript.

var y let nos permite crear variables que se pueden cambiar. Y const nos permite crer variables que no se pueden cambiar.

6. Control de Flujo:

¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?

Son los ciclos (while, for) y los condicionales (if - else)

7. Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.

Una funcion de flecha es otra manera de declarar una funcion expresada donde en un bloque de codigo indicamos una serie de instrucciones para que se ejecute una tarea.

Asi seria funcion expresada..
let suma = function (a,b){
	return a+b 
}

Asi seria en function flecha..
let suma =  (a,b) => a+b

8. ¿Qué es JSON y cómo se utiliza en JavaScript?

Un JSON es una archivo de texto que contiene datos que se pueden consumir desde una aplicacion y para poderlo utilizar en JavaScript debe ser convertido a un objeto de JavaScript.

9. Promesas:

Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.

Una promesa es un recurso que nos ayuda a manejar los problemas de asincronia, es decir los problemas que ocurren cuando una tarea tiene que esperar a que otra termine para poder ejecutarse.

La promesa es algo que va a ocurrir en el futuro pero puede que esta promesa se de (aceptada) o no se de (rechazada).

10. ¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?

En JavaScript existe una herramienta que nos ayuda a encontrar errores en nuestro codigo de manera eficiente llamada Debugger.

## Preguntas de Selección Múltiple (20)

11. ¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
   - A) `var myVariable;`
   - B) `variable myVariable;`
   - C) `let myVariable;`
   - D) `A y C son correctas.` (X)

12. ¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
   - A) `push()` (X)
   - B) `pop()`
   - C) `shift()`
   - D) `unshift()`

13. ¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
   - A) `==`
   - B) `===` (X)
   - C) `!=`
   - D) `!==`

14. ¿Cuál es la salida del siguiente código?
   ```javascript
   console.log(typeof null);
   ```
   - A) `null`
   - B) `undefined` (X)
   - C) `object`
   - D) `number`

15. ¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
   - A) `forEach()` (X)
   - B) `map()`
   - C) `filter()`
   - D) `Todas las anteriores`

16. ¿Qué se entiende por “hoisting” en JavaScript?
   - A) Declaraciones de variables y funciones se mueven al principio de su ámbito. (X)
   - B) Es un término para describir la eliminación de variables.
   - C) Es un método para agrupar varias funciones.
   - D) Ninguna de las anteriores.

17. ¿Cuál es la diferencia entre `null` y `undefined` en JavaScript?
   - A) `null` significa que una variable ha sido declarada pero no definida, `undefined` significa que no se ha declarado.
   - B) `null` es un valor asignado intencionalmente, `undefined` significa que una variable no tiene valor. (X)
   - C) `undefined` es un valor asignado intencionalmente, `null` significa que una variable no tiene valor.
   - D) No hay diferencia.

18. ¿Cuál es el propósito del método `Array.prototype.map()`?
   - A) Modificar el array original.
   - B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original. (X)
   - C) Filtrar los elementos de un array.
   - D) Encontrar un elemento en un array.

19. ¿Qué es el `Event Loop` en JavaScript?
   - A) Un ciclo que controla las llamadas recursivas.
   - B) Un proceso que permite a JavaScript realizar operaciones asincrónicas. (X)
   - C) Un método para iterar sobre arrays.
   - D) Ninguna de las anteriores.

20. ¿Cuál es la salida del siguiente código?
    ```javascript
    console.log(0.1 + 0.2 === 0.3);
    ```
    - A) `true`
    - B) `false` (X)
    - C) `undefined`
    - D) `NaN`

21. ¿Qué se entiende por `strict mode` en JavaScript?
    - A) Un modo que permite utilizar características experimentales.
    - B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro. (X)
    - C) Un método para validar datos.
    - D) Ninguna de las anteriores. 

22. ¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?
    - A) `let obj = {};`
    - B) `let obj = Object.create();`
    - C) `let obj = new Object();`
    - D) A y C son correctas. (X)

23. ¿Qué es un `callback` en JavaScript?
    - A) Una función que se pasa como argumento a otra función. (X)
    - B) Un tipo de variable especial.
    - C) Un método para declarar funciones.
    - D) Ninguna de las anteriores.

24. ¿Cuál es el propósito de `async` y `await` en JavaScript?
    - A) Ejecutar funciones síncronas.
    - B) Manejar operaciones asincrónicas de manera más simple y legible. (X)
    - C) Declarar variables globales.
    - D) Ninguna de las anteriores.

25. ¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?
    - A) Arrays
    - B) Strings (X)
    - C) Objetos
    - D) Ninguna de las anteriores.

26. ¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?
    - A) `JSON.parse()`
    - B) `JSON.stringify()`(X)
    - C) `toString()`
    - D) `parseInt()`

27. ¿Qué es un `Promise` en JavaScript?
    - A) Una función que se ejecuta inmediatamente.
    - B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica. (X)
    - C) Un método para declarar variables.
    - D) Ninguna de las anteriores.

28. ¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?
    - A) `push()`
    - B) `pop()`
    - C) `shift()`
    - D) `unshift()`(X)

29. ¿Cuál es la diferencia entre `localStorage` y `sessionStorage` en JavaScript?
    - A) `localStorage` almacena datos solo durante la sesión del navegador, `sessionStorage` almacena datos de manera persistente.
    - B) `sessionStorage` almacena datos solo durante la sesión del navegador, `localStorage` almacena datos de manera persistente. (X)
    - C) No hay diferencia entre ellos.
    - D) Ambos almacenan datos solo durante la sesión del navegador.

30. ¿Qué método se utiliza para detener la propagación de un evento en el DOM?
    - A) `event.stopPropagation()`(X)
    - B) `event.preventDefault()`
    - C) `event.stop()`
    - D) `event.cancel()`