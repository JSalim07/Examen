## $Planificacion$ $de$ $procesos$

El objetivo de la multiprogramación es asegurarse de que siempre haya un proceso en ejecución, de modo que se aproveche al máximo el tiempo de la CPU. Por otro lado, el objetivo del tiempo compartido es alternar rápidamente entre varios procesos para que los usuarios puedan interactuar con cada uno de ellos mientras se están ejecutando, dando la sensación de que todos están corriendo al mismo tiempo.

## $Hablemos$ $de$ $los$ $algoritmos...$

### FCFS

El algoritmo **FIFO (Primero en Entrar, Primero en Salir)** o **FCFS (Primero en Llegar, Primero en Ser Atendido)** asigna el tiempo de CPU a los procesos según el orden en que llegan. El primer proceso que llega recibe el tiempo de CPU hasta que termina completamente. Luego, el siguiente proceso en la cola recibe su tiempo de CPU hasta que también termina, y así sucesivamente hasta que se completan todos los procesos. Este algoritmo se usa comúnmente para gestionar trabajos en colas de impresión, es decir, en el orden en que los trabajos van llegando a la impresora.

### Round Robin

En el algoritmo Round Robin cada proceso recibe un tiempo de CPU fijo, conocido como "quantum". Los procesos se ejecutan de manera cíclica, y cuando un proceso agota su tiempo asignado, pasa al siguiente proceso en la cola. Este enfoque asegura que todos los procesos tengan una oportunidad de ejecutarse de manera equitativa y se utiliza principalmente en sistemas con múltiples procesos simultáneos.

### SJF

El algoritmo SJF (Shortest Job First) selecciona el proceso con el tiempo de ejecución más corto para ejecutarlo primero. Su objetivo es minimizar el tiempo de espera total y mejorar la eficiencia, ya que los procesos más rápidos se completan primero, lo que reduce el tiempo de espera de otros procesos en la cola.

Existen dos versiones de SJF:

- **SJF no preemptivo:** Una vez que un proceso comienza a ejecutarse, no se interrumpe, incluso si llega un proceso más corto.

- **SJF preemptivo (también conocido como PSJF):** Si un proceso más corto llega mientras se está ejecutando otro proceso, el proceso actual se interrumpe y el más corto es ejecutado primero.
