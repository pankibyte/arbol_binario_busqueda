Arbol binario de busqueda
Aquí se encuentra el TDA Arbol binario de busqueda, en el cual se pueden utilizar las primitivas declaradas en el archivo arbol.h , en el cual el usuario deberá saber que tipo de datos está manejando en sus tests/trabajo dentro del arbol. 
Para poder compilarlo deberá utilizar ésta linea en la terminal:gcc *.c -o abb -g -std=c99 -Wall -Wconversion -Wtype-limits -pedantic -Werror -O0
Y para poder correr el programa y tener la visión de la memoria utilizada:valgrind --leak-check=full --track-origins=yes --show-reachable=yes ./abb
  
El Arbol binario de busqueda es un arbol binario que puede ser vacio o puede en cada nodo tener un valor o clave. A diferencia del arbol binario, no es necesario por donde ir en su estructura, ya que el arbol binario de busqueda cuenta con sus operaciones de busqueda. Además tiene una ventaja en la busqueda que su tiempo en el peor caso será O(n), y en el mejor, log(n)

La opción de tener el destructor, hace que el usuario pueda manejar sus datos ingresados en el arbol, o sea, puede ingresar desde enteros o arrays, hasta otros datos abstractos.

complejidades algoritmicas:

Busqueda: Peor caso O(n) , mejor caso log(n)
Insertar: Peor caso O(n), mejor caso log(n)
Borrar: Peor caso O(n), mejor caso log(n)
