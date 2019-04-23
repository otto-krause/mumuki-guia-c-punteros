<h4> Alguna vez viste algo como esto adentro de tu computadora?</h4>
<img src="https://raw.githubusercontent.com/otto-krause/mumuki-guia-c-punteros/master/assets/CT51264BD160BJ-01_1556028611596.jpg" alt="CT51264BD160BJ-01_1556028611596.jpg" width="30%" height="auto">

Se llama memoria ram, y es donde viven nuestros programas cuando los ejecutamos.<br>

Imaginemos que en el medio de nuestro programa están creadas las siguientes variables:

``` c
 int a = 4; 
 int b = 5; 
 int c = 9; 
```

 
 Todas estas variables van a guardar sus valores en algún lugar de la memoria ram, veamos el siguiente gráfico:
 
 <img src="https://raw.githubusercontent.com/otto-krause/mumuki-guia-c-punteros/master/assets/ejemplo%20ram_1552656721531.png" alt="ejemplo ram_1552656721531.png" width="auto" height="auto">
 
 En el gráfico observamos que la ram está dividida en diferentes partes, en color negro vemos los valores almacenados, y en color rojo las diferentes direcciones de memoria. Como conclusión podemos decir que la variable `a` guarda su valor en la dirección de memoria 2345, la variable `b` lo guarda en la dirección 2346 y la variable `c` en la 2347;
 
 <br>
 Si quisieramos ver las direcciones de memoria en nuestro programa deberíamos hacer los siguiente:
 
 ``` c
 printf("Dirección a: %d, Dirección b: %d, Dirección c: %d",&a,&b,&c);
```

 Notemos que poniendo **&** adelante de la variable obtenemos su dirección de memoria como un valor entero.