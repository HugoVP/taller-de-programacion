# taller-de-programacion
Teoria y ejercicios de programacion

Modulo I - Elementos Basicos

Ejercicios

1. Escribir un programa que escriba datos personales, como el nombre y la direccion.
2. Escribir un programa que escriba la palabra HOLA usando caracteres, como asterisco, por ejemplo.
   Nota: Las dimesiones de cada letra son 6 x 7 caracteres.

3. Escribir un programa que pregunte al usuario los siguientes datos:
  - Nombre
  - Apellidos
  - Edad
  - Fecha de nacimiento
  - Lugar de nacimiento
  - Ocupacion

  El programa debera escribir una pequenia biografia del usuario tomando como base sus datos capturados, ejemplo:
  
  "**Juan Perez** tiene **38** anios de edad.
   Nacio el **1 de enero de 1985**, en **Ciudad de Mexico**.
   Actualmente trabaja como **chofer**."

Modulo II - Variables

2.1 Las variables son contenedores que almacenan valores de datos.

Declaracion y definicion de variables

En Python las variables no se declaran explicitamente. Estas se crean al momento en que se les asigna un valor (definicion).

Ejemplos:

foo = 5
bar = 12.5
baz = True
qux = "Hello World!"
xyz = 'C'

Las variables no necesitan ser declaradas con un tipo de dato en particular, y pueden cambiar su tipo despues de haber sido definidas.

Ejemplos:

foobar = 4
foobar = "Lorem ipsum"

Conversion de variables (Casting)

El tipo de una variable puede ser cambiado practicamente a voluntad usando funciones de conversion (cast). y puede ser una manera de ser explicitos al momomento de definir una variable.

Ejemplos:

foobar = str(5)      # el valor de foobar es de tipo string, o sea '5' o "5"
foobar = int(5)      # el valor de foobar es de tipo entero, o sea 5
foobar = float(5)    # el valor de foobar es de tipo flotante, o sea 5.0
foobar = bool(5)     # el valor de foobar es de tipo booleano, o sea True (True para todo valor diferente de 0, False para 0)

Obtener el tipo de una variable

Para obtener el tipo de una variable en Python usamos la funcion type().

Ejemplos:

foobar = 10
baz = "John Doe"

type(foobar)
type(baz)

Distinguen entre mayusculas y minusculas

Los nombres de variables en Python, y en muchos otros lenguajes de programacion, distinguen entre mayusculas y minusculas

foobar = 123
FooBar = "Hello World!"
Foobar = True

2.2 Reglas de los nombres de variables en Python

Las reglas que siguen los nombres de las variables en Python son las siguientes:

- Deben empezar con una letra o un guion bajo (_).
- No puede iniciar con numeros
- Solo puede contener caracteres alfanumericos o guiones bajos (a-zA-Z0-9_)
- Distinguen entre mayusculas y minusculas

Ejemplos de nombres de variables incorrectos:

123foobar = 123
foo-bar = 123
foo bar = 123

2.3 Asignacion de multiples valores

2.3.1 Varios valores a multiples variables

Python permite asignar valores a multiples variables al mismo tiempo:

Ejemplo:

x, y, z = "Verde", "Blanco", "Rojo"

Solo se debe de asegurar de que el numero de valores corresponda con el numero de variables.

2.3.1 Un valor a multiples variables

Un mismo valor puede asignarse a multiples variables en una misma linea de codigo

Ejemplos:

foobar = baz = xyz = "Hello World!"

2.4 Desempaquetar una coleccion

Si se tiene una coleccion (un objeto con multiples valores), Python permite extraer cada uno de sus valores en variables.

Ejemplos:

frutas = \["manzana", "platano", "fresa"\]
f1, f2, f3 = frutas.





