**Actividad**

**(tablero4)**

Modificar tablero1 y añadir:

- haz una función que retorne un color al azar.
- al recargar de la página, cambiar los colores de todas las cajas.
- clic en la caja, ponerla en blanco y cambiar los colores de las demás.

\* grupo-TABLERO4-expediente-ApellidosNombre.htm 


**Actividad**

**(tablero5)**

Diseña tu propio tablero. Añade nuevas características.

\* grupo-TABLERO5-expediente-ApellidosNombre.htm


**Actividad**

**(nif)**

Crea un programa en JS para verificar la letra y el número del NIF.

- pedir datos al usuario (prompt): número y letra
- realizar los chequeos de entra de datos (try..catch..finally)
- imprimir los datos de entrada (document.write)
- imprimir detalle del error si lo hay (catch..throw)
- imprimir resumen si hubo o no error

[popup dasaconsejado] https://neoattack.com/neowiki/pop-up/

\* grupo-NIF-expediente-ApellidosNombre.htm 


**Actividad**

**(listas3)**

Añade atributos a los objetos y pintar cada uno como un div.

- alto=al azar entre: 50,70,90
- ancho=al azar entre: 40,60
- color=aleatorio RGB
- texto=una letra al azar 'ABCDEFGHIJKL'
- nivel=a, b, c 
- versión=al azar entre 0..9

Crea un div contenedor para cada lista de div. Muestra estas listas:

- Listado en orden del índice del array
- Ascendente por versión
- Descendente or versión
- Filtrado por versión de 0 a 5
- Suma de las versiones

\* grupo-LISTAS3-expediente-ApellidosNombre.htm 


**Actividad**

**(enteros.htm)**

Haremos un página de entrada de datos.

- Añade N elementos textArea a tu página. N puede valer entre 2 y 20

En este orden chequea:

- Si todos están rellenos y son enteros muestra los números ordenados ascendente y descendente
- Si todas las cajas están rellenas pero alguna no tiene un entero muestra 'hay entradas que no son enteros' 
- Si alguna esta vacía 'faltan X por rellenar complete'
- Si alguna entrada no es un número entero muestra 'alguna no es entero'
- Si todos están vacíos, solicita al usuario 'rellene con números enteros'

Lenguaje: [], push, for..of, filter, sort, parseInt, join, isNaN, =>, textarea , pre

Puedes rehacer el ejercicio con tus propios chequeos y mensajes.

\* grupo-ENTEROS-expediente-ApellidosNombre.htm 


**Actividad**

**(tablaValores)**

- Crea una tabla con los valores del seno y coseno y los campos indicados. La precisión es 14 dígitos.
- Preséntala como texto
- Preséntala como una tabla con estilos [N1]
- Dibuja usando canvas la tabla de valores [N2](canvas)
- Lenguaje: class para table, Math, split, canvas, table-th-tr-td, className

\* grupo-TABLAVALORES-expediente-ApellidosNombre.htm


**Actividad**

**(menujs)**

Hacer un menú por niveles descendentes. Partimos de una lista de datos.

Tenemos una lista de localizaciones en diferentes niveles: continente, país, ciudad

indicados en el primer campo por la letra (A,B,C)

Estas localizaciones están enlazadas por el tercer campo.

- -Presentamos el primer nivel los continentes.
- -Al hacer un clic sobre el continente tenemos que presentar los países de ese continente.
- -Así sucesivamente.
- -Presentar una lista de migas para informar en que nivel estamos

Ampliación:

- Añadir más datos
- Añadir más niveles 
- Hacer la lista de migas sea ‘clicable’ y mostrar el menú correspondiente
- Usar una lista de objetos para el array sitios y los métodos de array

Lenguaje: div, [], push, for of, for in, split, addEventListener, :hover, className, innerHTML=''

var sitios=[]

Datos:

'A1#america#00',

'A2#europa#00',

'A3#africa#00',

'A4#asia#00',

'B1#canada#A1',

'B2#eeuu#A1',

'B3#brasil#A1',

'B4#argentina#A1',

'B5#urugay#A1',

'B6#chile#A1',

'B7#francia#A2',

'B8#italia#A2',

'C1#toronto#B1',

'C2#quebec#B1',

'C3#lyon#B7',

'C4#paris#B7',

'C5#bayona#B7',

'C6#nantes#B7',

'C7#toulouse#B7'

];

\* grupo-MENUJS-expediente-ApellidosNombre.htm 


**Actividad**

**(fechas)**

Ejercicio para el tema de fechas.

1) añadimos un control input type date y el evento change para imprimir una fecha en formato corto
1) almacenamos 24 fechas generadas al azar en un array. las fechas es cualquier dia del año 2019
1) organizar las fechas en un display a 6 columnas
1) resolver las operaciones con el array de objetos fechas

Lenguaje: [], push, new Date, setDate, getDate, sort(funtion), input type date, (1000\*60\*60\*24), toFixed, getDate, getMonth, getFullYear, getTime, padStart

\* grupo-FECHAS-expediente-ApellidosNombre.htm
