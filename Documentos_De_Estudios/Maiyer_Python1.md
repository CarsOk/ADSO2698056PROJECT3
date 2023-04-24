# Python

este lenguaje contiene los siguientes definiciones de sus variables

float = sirve para decirle al interprete que va a trabajr con numeros reales (permite decimales)
int = sirve para decirle al interprete que va a trabajar con numeros enteros (no permite decimales)
Boolean = sirve para decirle al interprete si es verdadero o falso (True/false)
String = sirve para decirle al interprete que va a trabajr con cadenas de texto , aunque el interprete siempre lo tomara como cadena de texto a menos que le digamos que esa variable va a ser cambiada a algun otro tipo

## Condicionales
Sintaxis
if ():
 
Esta seria la sintaxis y para que nuestro if realice una accion solo si se cumple la condicion tiene que estar indentado debajo del if vasta con presionando tab o 4 o 4  veces espacio.

si queremos que nustro codigo realice algo si no se cumple nuestra condicion del if podemos usar Else de la 
siguiente manera

if():
    print ("Hello world")
else :
    print(No se cumplio la condicion)

En este caso si no se cumple nuestra condicion del if nuestro condicional va a entrar al else y va a realizar lo que tengamos indentado dentro de este

Si queremos agregar otra condicion aparte de la inicial de nuestro if podemos usar elif como en el ejemplo a continnuacion

if (2):
    print("Hello")
elif (1):
    Print("World")

asi usamos este condicional y podemos usar tantos como necesitemos en nuestro codigo

## Ciclos

Ciclo "For" Este ciclo tiene la siguiente sintaxis.

for (i) in range (1,5,1):
    Print(i)

En este caso nuestra variable "i" es la variabl que va incrementar su valor hasta que alcance el numero que le colocamos en "in range" (valor inicial,valor final,con paso) como vemos en el ejemplo anterior a i le estamos dando un valor inicial de 1 y le estamos diciendo que se salga del ciclo cuando i llegue a 5 y que va a subir su valor en 1 cada vez que se repita nuestro ciclo

Ciclo "While" este ciclo tiene la siguiente Sintaxis

while () :

Este ciclo se va a ejecutar todo lo que este indentado mientras no se cumpla la condicion que le coloquemos, este ciclo es muy sencillo y legible solo se debe tener en cuenta que se pueda cumplir la condicion para que el ciclo no quede infinito

