Un puntero es una variable que se destina específicamente a guardar direcciones de memoria.<br>
¿Qué utilidad tiene esto? Muchas, ya lo vas a ver en las guías de vectores y funciones.
<br>
Observemos el siguiente código:

``` c
int * a;
char * b;
float * c;
```
Los punteros se declaran con un asterisco y un tipo de dato, por lo tanto `a` apunta a una variable de tipo int, `b`
 apunta a una variable de tipo char.
 <br>

¿Como se usan?

``` c
printf("La variable a guarda la dirección de memoria %d, y dentro de esa dirección de memoria hay: %d", a, *a);
```
Si imprimimos por pantalla `a` vamos a obtener la dirección de memoria que almacena el puntero, en cambio si imprimimos `*a` la función va a acceder a memoria ram y va a mostrar cual es el valor que se almacena en esa dirección de memoria.

