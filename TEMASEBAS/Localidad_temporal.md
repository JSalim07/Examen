<style>
    body {
        font-family: "Times New Roman", Times, serif;
    }
</style>

### La **localidad temporal** es un principio en el mundo de la informática, pues refiere al hecho de que si algún dato es utilizado, muy probablemente este mismo dato sea usado en un futuro cercano.

----------

### Bien, ya vimos la definición, un ejemplo:
- <span style="font-size: 16px;">Cuando en un bucle se accede repetidamente a una variable, pues esa variable será usada una y otra vez en un periodo corto de tiempo.</span>

## ¿Pero cuál es su uso en los sistemas de memorias?
### Esto es muy usado en el diseño de los **cachés**, pues los datos que usan recientemente se mantienen cerca del procesador debido a que se espera que sean reutilizados pronto.

### Pero no solo se usa en el caché, sino que también en la administración de páginas en la memoria virtual, un ejemplo: el algoritmo LRU (Least Recently Used).
<span style="font-size: 18px;">Ejemplo en una práctica (en lenguaje C):</span>

- <span style="font-size: 15px;">En un programa, si una instrucción o dato en memoria es accedido (por ejemplo, el contenido de una variable o un bloque de código dentro de un bucle), el sistema anticipará que este será necesario otra vez en un intervalo corto.
 (Lo que se ve en esta práctica)</span>

    - ``` c
        for (int i = 0; i < 100; i++) {
            sum += array[i];
        }
        ```


# 

## Mejora del Rendimiento

| Aspecto | Descripción |
|---------|-------------|
| Localidad Temporal | Aprovechar la localidad temporal reduce el tiempo de espera del procesador, ya que los datos se encuentran más cerca (en la caché), lo que mejora la velocidad de ejecución de los programas. |

## Diseño de Sistemas Operativos

| Aspecto | Descripción |
|---------|-------------|
| Gestión de Memoria Virtual | Los algoritmos de gestión de memoria virtual (como reemplazo de páginas) consideran la localidad temporal para decidir qué datos mantener en memoria principal. |

## Aplicaciones de la Localidad Temporal

| Área | Descripción |
|------|-------------|
| Cachés de CPU | Los datos accedidos recientemente se mantienen en caché porque es probable que se necesiten de nuevo. |
| Sistemas de Archivos | Los sistemas operativos almacenan en caché los bloques de disco accedidos recientemente. |
| Optimización de Software | Los compiladores y programadores diseñan algoritmos y estructuras de datos que aprovechan la localidad temporal. |
