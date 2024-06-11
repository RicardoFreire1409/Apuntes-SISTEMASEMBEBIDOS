#Memoria Virtual de un proceso
Un *proceso* es un _programa en ejecución_. Un programa es un archivo ejecutable, este se agenda y la CPU procede a ejecutarlo.
La memoria virtual es la memoria que el programa tiene a su disposición.
La asignación estática de memoria es efectuada en tiempo de compilación. Usada para variables globales.

##Asignación automática de memoria
Se efectúa en el stack (sección de memoria reservada para el almacenamiento de funciones).
Las funciones necesitan memoria para almacenar parámetros, variables locales, variables de retorno.
El *stack frame* es todo el espacio de memoria que necesita la función para ejecutarse.
Se llama asignación automática porque es efectuada en tiempo de ejecución y se libera al terminar la misma.
//int = 4 bytes
El stack crece/decrece en tiempo de ejecución.

##Asignación dinámica de memoria
Es efectuada en tiempo de ejecución. 
* Explícito: Se reserva o libera memoria de forma arbitraria.
* Implícito: Un proceso gestionador de memoria detecta cuando un bloque reservado ya no es usado y la libera automáticamente.

