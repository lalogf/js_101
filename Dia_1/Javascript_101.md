# Javascript

## Introducción

### ¿Qué es Javascript?

Javascript es un lenguaje de programación que corre en el front-end (client side) y en el back-end (server-side).

Está basado en ECMAScript y sigue sus patrones. Mira más información [aquí](https://es.wikipedia.org/wiki/ECMAScript).

HTML y CSS son guías de estilo y layout que le dicen al navegador que mostrarle al usuario. Javascript es una lista detallada de operaciones que pueden responder a eventos y cambiar cosas en la página [(DOM).](https://es.wikipedia.org/wiki/Document_Object_Model)


## ¿Qué puede hacer Javascript?

Javascript es responsable de añadir funcionalidad a las interfaces web. Aquí una lista de cosas que JS puede hacer:

* Asignar eventos a elementos del DOM, como eventos cuando se hace clic o mouseover.
* Animaciones como fades o slides
* AJAX para obtener datos del servidor después de la carga inicial de la página
* Dibujos de vectores avanzados y animaciones junto con el canvas de HTML5.
* Aplicaciones móviles híbridas
* Mucho más

## Tipos de Datos

Existen 6 tipos de valores en JavaScript: 

* numbers
* strings
* booleans
* objects
* functions
* undefined values


##Numbers

JavaScript uses a fixed number of bits, namely 64 of them, to store a single number value. There are only so many patterns you can make with 64 bits, which means that the amount of different numbers that can be represented is limited. For N decimal digits, the amount of numbers that can be represented is 10N. Similarly, given 64 binary digits, you can represent 264 different numbers, which is about 18 quintillion (an 18 with 18 zeros after it). This is a lot.

Fractional numbers are written by using a dot.

9.81
For very big or very small numbers, you can also use scientific notation by adding an “e” (for “exponent”), followed by the exponent of the number:

2.998e8


The main thing to do with numbers is arithmetic. 

When operators appear together without parentheses, the order in which they are applied is determined by the precedence of the operators. 

There is one more arithmetic operator, which you might not immediately recognize. The % symbol is used to represent the remainder operation. X % Y is the remainder of dividing X by Y. For example, 314 % 100 produces 14, and 144 % 12 gives 0. 

##Strings

Strings are used to represent text. They are written by enclosing their content in quotes.

Almost anything can be put between quotes, and JavaScript will make a string value out of it.

Newlines (the characters you get when you press Enter) also can’t be put between quotes. The string has to stay on a single line.

Take the following string:

"This is the first line\nAnd this is the second"
The actual text contained is this:

This is the first line
And this is the second
There are, of course, situations where you want a backslash in a string to be just a backslash, not a special code. If two backslashes follow each other, they will collapse together, and only one will be left in the resulting string value. This is how the string “A newline character is written like "\n".” can be expressed:

"A newline character is written like \"\\n\"."
Strings cannot be divided, multiplied, or subtracted, but the + operator can be used on them. It does not add, but it concatenates—it glues two strings together. The following line will produce the string "concatenate":

"con" + "cat" + "e" + "nate"

##Boolean

Often, you will need a value that simply distinguishes between two possibilities, like “yes” and “no” or “on” and “off”. For this, JavaScript has a Boolean type, which has just two values: true and false (which are written simply as those words).


##Expressions and statements

##Variables

* Variable names can be any word that isn’t a reserved word (such as var). 
* They may not include spaces. 
* Digits can also be part of variable names—catch22 is a valid name, for example—but the name must not start with a digit. 
* A variable name cannot include punctuation, except for the characters $ and _

### Reserved words

~~~ js 
do
if
in
for
let
new
try
var
case
else
enum
eval
null
this
true
void
with
await
break
catch
class
const
false
super
throw
while
yield
delete
export
import
public
return
static
switch
typeof
default
extends
finally
package
private
continue
debugger
function
arguments
interface
protected
implements
instanceof
~~~


## Functions

A function is a piece of program wrapped in a value. Such values can be applied in order to run the wrapped program. For example, in a browser environment, the variable alert holds a function that shows a little dialog box with a message.

* Executing a function is called invoking, calling, or applying it. 
* You can call a function by putting parentheses after an expression that produces a function value. 
* Usually you’ll directly use the name of the variable that holds the function. 
* The values between the parentheses are given to the program inside the function. 
* Values given to functions are called arguments.