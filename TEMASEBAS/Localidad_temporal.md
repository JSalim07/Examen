### La **localidad temporal** es un principio en el mundo de la informatica, pues refiere al hecho de que si algun dato es utilizado, muy probablemente este mismo dato sea usado en un futuro cercano.
<span style="font-size: 16px;"></span>

----------
### Bien, ya vimos la definición, un ejemplo:
- <span style="font-size: 16px;">Cuando en un bucle se accede repetidamente a una variable, pues esa variable sera usada una y otra vez en un periodo corto de tiempo.</span>

## ¿Pero cual es su uso en los sistemas de memorias?
### Esto es muy usado el diseño de los **cachés**, pues los datos que usan recientemente se mantienen cerca del procesador debido a que se espera que sean reutilizados pronto.

### Pero no solo se usa en el caché, sino, que también en la administración de paginas en la memoria virtual, un ejemplo: el algoritmo LRU( Least Recently Used).
<span style="font-size: 18px;">Ejemplo en una practica (en lenguaje c):</span>

- <span style="font-size: 15px;">En un programa, si una instrucción o dato en memoria es accedido (por ejemplo, el contenido de una variable o un bloque de código dentro de un bucle), el sistema anticipará que este será necesario otra vez en un intervalo corto.
 (Lo que se ve en esta practica)</span> 

    - ``` c
        for (int i = 0; i < 100; i++) {
            sum += array[i];
        }
        ```
<span style="font-size: 16px;"> Aquí, cada acceso a array[i] es un ejemplo de localidad temporal, ya que el programa accede repetidamente a valores dentro del mismo bloque de datos en un período corto.
</span>

# 
# Importancia de la localidad temporal
## Optimización de la Caché
<span style="font-size: 15px;">Los sistemas modernos utilizan memorias caché para almacenar datos que probablemente se reutilicen pronto. Esto reduce la necesidad de acceder a memorias más lentas como RAM o almacenamiento secundario.
</span>

## Mejora del Rendimiento
<span style="font-size: 15px;">Aprovechar la localidad temporal reduce el tiempo de espera del procesador, ya que los datos se encuentran más cerca (en la caché), lo que mejora la velocidad de ejecución de los programas.</span>

## Diseño de Sistemas Operativos
<span style="font-size: 16px;">Los algoritmos de gestión de memoria virtual (como reemplazo de páginas) consideran la localidad temporal para decidir qué datos mantener en memoria principal.</span>

# . . .
# Como se puede aplicar dicha localidad temporal?
<span style="font-size: 17px;">Cachés de CPU: </span>
<span style="font-size: 16px;">Los datos accedidos recientemente se mantienen en caché porque es probable que se necesiten de nuevo.
</span>

<span style="font-size: 17px;">Sistemas de archivos:
</span>
<span style="font-size: 16px;">Los sistemas operativos almacenan en caché los bloques de disco accedidos recientemente.
</span>

<span style="font-size: 17px;">Optimización de Software:
</span>
<span style="font-size: 16px;">Los compiladores y programadores diseñan algoritmos y estructuras de datos teniendo en cuenta este principio para mejorar el uso de la memoria.
</span>
