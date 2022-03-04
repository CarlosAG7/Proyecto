
# Qué es Python?
Python es un lenguaje sencillo de leer y escribir debido a su alta similitud con el lenguaje humano. Además, se trata de un lenguaje multiplataforma de código abierto y, por lo tanto, gratuito, lo que permite desarrollar software sin límites. Con el paso del tiempo, Python ha ido ganando adeptos gracias a su sencillez y a sus amplias posibilidades, sobre todo en los últimos años, ya que facilita trabajar con inteligencia artificial, big data, machine learning y data science, entre muchos otros campos en auge. 

# Qué es una variable?
Es algo que puede cambiar, que no es constante.

→ Una variable consta de dos elemento esenciales.

→ un identificador o nombre de variable

Un valor que puede ser otro identificador o un dato de cualquier tipo como un número, una cadena de texto o string, un valor booleano, etc.
Para asignar o asociar un valor a un identificar o nombre de variable se suele emplear un símbolo matemático o lógico, definido en la sintaxis del lenguaje de programación que se esté empleando, que pueda significar asignación y es comúnmente el símbolo «igual» (=).

## Nombrando una variable
Una variable es un espacio de la memoria del ordenador a la que asignamos un contenido que puede ser un valor numérico (sólo números, con su valor de cálculo) o alfanumérico (sólo texto o texto con números). Cada variable tiene un único nombre el cual no puede ser cambiado. Dos o más variables pueden tener el mismo contenido, pero no el mismo nombre. El nombre de una variable comenzará siempre por una letra, pudiendo contener a continuación tanto letras como números. 

Las letras pueden ser tanto mayúsculas como minúsculas. No se admiten nombres de variables incluyendo espacios en blanco ni símbolos especiales como guiones, puntos, comas, comillas, etc. ni símbolos matemáticos ni palabras clave (que veremos más adelante, y que incluyen “inicio”, “fin”, “verdadero”, “falso”,    “entonces”...). El nombre de una variable será lo suficientemente largo como para impedir que pueda confundirse con otra variable por tener nombre similar, así como para aportar una indicación de cuál es el contenido o función que cumple.

## Asignando valores a una variable
Las variables en Python se crean cuando se definen por primera vez, es decir, cuando se les asigna un valor por primera vez. Para asignar un valor a una variable se utiliza el operador de igualdad (=). A la izquierda de la igualdad se escribe el nombre de la variable y a la derecha el valor que se quiere dar a la variable.

En el ejemplo siguiente se almacena el número decimal 2.5 en una variable de nombre x (como se comenta en el apartado anterior, realmente habría que decir que se crea la etiqueta x para hacer referencia al objeto número decimal 2.5). Fíjese en que los números decimales se escriben con punto (.) y no con coma (,).

x = 2.5
## Operadores básicos
→ suma (+)

→ resta (-)

→ multiplicacion (*)

→ division (/)

→ division euclidiana (cociente)(//)

→ módulo (%)

→ potencia (** )

### Suma
(+) es el operador de suma. Se utiliza para sumar 2 valores.

Ejemplo :

val1 = 2

val2 = 3

usando el operador de adición

res = val1 + val2

print(res)

Salida :

5
### Resta
(-) es el operador de sustracción. Se utiliza para restar el segundo valor del primer valor.

Ejemplo :

val1 = 2

val2 = 3

Usando el operador de resta

res = val1 - val2

print(res)

Salida :

-1
### Multiplicación
(*) es el operador de multiplicación. Se utiliza para encontrar el producto de 2 valores.

Ejemplo :

val1 = 2

val2 = 3

usando el operador de multiplicación

res = val1 * val2

print(res)

Salida :

6

### División
(/) es el operador de división. Se utiliza para encontrar el cociente cuando el primer operando se divide por el segundo.

Ejemplo :

val1 = 3

val2 = 2

Usando el operador de división

res = val1 / val2

print(res)

Salida :

1.5

### Módulo
% es el operador de módulo. Se utiliza para encontrar el resto cuando el primer operando se divide por el segundo.

Ejemplo :

val1 = 3

val2 = 2

usando el operador de módulo

res = val1 % val2

print(res)

Salida :

1
# Tipos de datos en Python
→ Numeros enteros

→ Numeros de punto flotante

→ Texto (cadenas de caracteres)

→ Booleanos (Verdadero y falso)

## Integer
Los números enteros son aquellos que no tienen decimales, tanto positivos como negativos (además del cero). En Python se pueden representar mediante el tipo int (de integer, entero) o el tipo long (largo). La única diferencia es que el tipo long permite almacenarnúmeros más grandes. Es aconsejable no utilizar el tipo long a menos que sea necesario, para no malgastar memoria. 

## Float
Los números reales son los que tienen decimales. En Python se expresan mediante el tipo float. En otros lenguajes de programación, como C, tiene también el tipo double, similar a float pero de mayor precisión (double = doble precisión).

## String
Los cadenas (o strings) son un tipo de datos compuestos por secuencias de caracteres que representan texto. Estas cadenas de texto son de tipo str y se delimitan mediante el uso de comillas simples o dobles.

## Casting en Python
Hacer un cast o casting significa convertir un tipo de dato a otro. Anteriormente hemos visto tipos como los int, string o float. Pues bien, es posible convertir de un tipo a otro.

Pero antes de nada, veamos los diferentes tipos de cast o conversión de tipos que se pueden hacer. Existen dos:

Conversión implícita: Es realizada automáticamente por Python. Sucede cuando realizamos ciertas operaciones con dos tipos distintos.

Conversión explícita: Es realizada expresamente por nosotros, como por ejemplo convertir de str a int con str().

## List
Una lista es una estructura de datos en Python que es una secuencia de elementos ordenados mutables o cambiables. Cada elemento o valor que está dentro de una lista se denomina elemento. Así como las cadenas se definen como caracteres entre comillas, las listas se definen con valores entre corchetes [ ]

## Tuple
Una tupla es una colección de objetos de Python separados por comas. De alguna manera, una tupla es similar a una lista en términos de indexación, objetos anidados y repetición, pero una tupla es inmutable a diferencia de las listas que son mutables.

## Dictionary
Un Diccionario es una estructura de datos y un tipo de dato en Python con características especiales que nos permite almacenar cualquier tipo de valor como enteros, cadenas, listas e incluso otras funciones. Estos diccionarios nos permiten además identificar cada elemento por una clave (Key).

# Tomando decisiones
→ If

→ For

→ While

→Break 

→ Continue
## Sentencia if
En la sentencia if sólo tienes un bloque de sentencias y este bloque se ejecuta sólo cuando la condición es True, se ignora cuando la condición es False.

El cuerpo de la declaración if en Python no está rodeado por llaves, sino que se usa la indentación. El final del cuerpo se indica con la primera línea no deseada.

## Ciclo For
El bucle for se utiliza para recorrer los elementos de un objeto iterable (lista, tupla, conjunto, diccionario, …) y ejecutar un bloque de código. En cada paso de la iteración se tiene en cuenta a un único elemento del objeto iterable, sobre el cuál se pueden aplicar una serie de operaciones.

## Ciclo While
El bucle while evalúa una condición y luego ejecuta un bloque de código si la condición es verdadera. El bloque de código se ejecuta repetidamente hasta que la condición llega ser o es falsa.

## Break
En Python, la instrucción break le proporciona la oportunidad de cerrar un bucle cuando se activa una condición externa. Debe poner la instrucción break dentro del bloque de código bajo la instrucción de su bucle, generalmente después de una instrucción if condicional. 

## Continue
La instrucción continue da la opción de omitir la parte de un bucle en la que se activa una condición externa, pero continuar para completar el resto del bucle. Es decir, la iteración actual del bucle se interrumpirá, pero el programa volverá a la parte superior del bucle.

La instrucción continue se encuentra dentro del bloque de código abajo de la instrucción del bucle, generalmente después de una instrucción if condicional. 
