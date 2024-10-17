# JS | Algoritmos básicos

El propósito de este ejercicio es practicas las estructuras de control de JavaScript.

## Introducción

Será una actividad en Pair-Programming utilizando algún programa del tipo de [repl.it](https://repl.it/) o el editor VSC+Node;

## Ejercicio

### Nombres y entrada de datos

1. Crea una variable `driver1` con el nombre del *driver*

2. Imprime  `"El nombre del driver es XXXX"`; 

3. Crea una variable `driver2` and [ask the user](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt) para el *navigator*

4. Imprime `"El nombre del navegador es YYYY"`

### Conditionales

5. Dependiendo de quién tenga el nombre más largo [is longer](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/length), imprime:
	- `The Driver tiene el nombre más largo, tiene XX caracteres` o 
	- `Yo, navegador tengo el nombre más largo, tiene XX caracteres` o
	- `Vaya, ambos nombres son iguales, XX caracteres!!`

### Bucles

6. Imprime todos los caracteres del nombre del  *driver*, separado por un espacio y en [mayúsculas](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toUpperCase)
  ej.: `"R A U L"`
  
7. Imprime el nombre del *navigator* en order inverso. 
  ej.: `"luaR"`
  
8. Dependiendo del orden alfabético [lexicographic order](https://en.wikipedia.org/wiki/Lexicographical_order) de las cadenas, imprime:
  - `El nombre del driver va primero`
  - `Yo, el navigator voy primero`
  - `Increíble! Ambos tenemos el mismo nombre?`

### Bonus Time!

9. Pedir al usuario un nuevo string y comprobar si es un [Palindrome](https://es.wikipedia.org/wiki/Pal%C3%ADndromo)

Ejemplos de palíndromos:

	- "A man, a plan, a canal, Panama!"
	- "Amor, Roma"
	- "race car"
	- "Ana lleva al oso la avellana"
	- "Senén té sis nens i set nenes"
	- "Ésope reste ici et se repose"
	- "I topi non avevano nipoti"
	- "Sator Arepo tenet opera rotas".

10. Ir al [lorem ipsum generator](http://www.lipsum.com/) y:
  - Generar 3 párrafos. Almacenar el texto en un String
  - Hacer que el programa cuente el número de palabras en el string
  - Hacer que el programa cuente el número de veces que aparece la palabra latina [`et`](https://en.wiktionary.org/wiki/et#Latin)

## Para más información

- [prompt() - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Window/prompt) | Ask user for input
- [String - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)
- [if - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
- [while - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while)
- [for - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for)